# ![LOGO](logo.png) BlueprintClient **flow**ground Connector

## Description

A generated **flow**ground connector for the BlueprintClient API (version 2018-11-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/blueprint-blueprintDefinition/2018-11-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:41+03:00

## API Description

Azure Blueprints Client provides access to blueprint definitions, assignments, and artifacts, and related blueprint operations.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List blueprint definitions.

*Tags:* `Blueprint`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').

### Delete a blueprint definition.

*Tags:* `Blueprint`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `blueprintName` - _required_ - Name of the blueprint definition.

### Get a blueprint definition.

*Tags:* `Blueprint`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `blueprintName` - _required_ - Name of the blueprint definition.

### Create or update a blueprint definition.

*Tags:* `Blueprint`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `blueprintName` - _required_ - Name of the blueprint definition.

### List artifacts for a given blueprint definition.

*Tags:* `Artifact`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `blueprintName` - _required_ - Name of the blueprint definition.

### Delete a blueprint artifact.

*Tags:* `Artifact`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `blueprintName` - _required_ - Name of the blueprint definition.
* `artifactName` - _required_ - Name of the blueprint artifact.

### Get a blueprint artifact.

*Tags:* `Artifact`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `blueprintName` - _required_ - Name of the blueprint definition.
* `artifactName` - _required_ - Name of the blueprint artifact.

### Create or update blueprint artifact.

*Tags:* `Artifact`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `blueprintName` - _required_ - Name of the blueprint definition.
* `artifactName` - _required_ - Name of the blueprint artifact.

### List published versions of given blueprint definition.

*Tags:* `PublishedBlueprint`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `blueprintName` - _required_ - Name of the blueprint definition.

### Delete a published version of a blueprint definition.

*Tags:* `PublishedBlueprint`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `blueprintName` - _required_ - Name of the blueprint definition.
* `versionId` - _required_ - Version of the published blueprint definition.

### Get a published version of a blueprint definition.

*Tags:* `PublishedBlueprint`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `blueprintName` - _required_ - Name of the blueprint definition.
* `versionId` - _required_ - Version of the published blueprint definition.

### Publish a new version of the blueprint definition with the latest artifacts. Published blueprint definitions are immutable.

*Tags:* `PublishedBlueprint`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `blueprintName` - _required_ - Name of the blueprint definition.
* `versionId` - _required_ - Version of the published blueprint definition.

### List artifacts for a version of a published blueprint definition.

*Tags:* `PublishedArtifact`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `blueprintName` - _required_ - Name of the blueprint definition.
* `versionId` - _required_ - Version of the published blueprint definition.

### Get an artifact for a published blueprint definition.

*Tags:* `PublishedArtifact`

#### Input Parameters
* `api-version` - _required_ - Client API Version.
* `scope` - _required_ - The scope of the resource. Valid scopes are: management group (format: '/providers/Microsoft.Management/managementGroups/{managementGroup}'), subscription (format: '/subscriptions/{subscriptionId}').
* `blueprintName` - _required_ - Name of the blueprint definition.
* `versionId` - _required_ - Version of the published blueprint definition.
* `artifactName` - _required_ - Name of the blueprint artifact.

## License

**flow**ground :- Telekom iPaaS / azure-com-blueprint-blueprint-definition-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
