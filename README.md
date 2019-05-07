# ![LOGO](logo.png) Netlify's API definition **flow**ground Connector

## Description

A generated **flow**ground connector for the Netlify's API definition API (version 0.1.0).

Generated from: https://api.apis.guru/v2/specs/netlify.com/0.1.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:14+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### listAccountsForUser

### createAccount

### listAccountTypesForUser

### cancelAccount

#### Input Parameters
* `account_id` - _required_

### updateAccount

#### Input Parameters
* `account_id` - _required_

### listAccountAuditEvents

#### Input Parameters
* `query` - _optional_
* `log_type` - _optional_

### listPaymentMethodsForUser

### getSiteBuild

#### Input Parameters
* `build_id` - _required_

### updateSiteBuildLog

#### Input Parameters
* `build_id` - _required_

### notifyBuildStart

#### Input Parameters
* `build_id` - _required_

### listDeployKeys

### createDeployKey

### deleteDeployKey

#### Input Parameters
* `key_id` - _required_

### getDeployKey

#### Input Parameters
* `key_id` - _required_

### getDeploy

#### Input Parameters
* `deploy_id` - _required_

### uploadDeployFile

#### Input Parameters
* `deploy_id` - _required_
* `path` - _required_

### uploadDeployFunction

#### Input Parameters
* `deploy_id` - _required_
* `name` - _required_
* `runtime` - _optional_

### lockDeploy

#### Input Parameters
* `deploy_id` - _required_

### unlockDeploy

#### Input Parameters
* `deploy_id` - _required_

### listForms

#### Input Parameters
* `site_id` - _optional_

### listFormSubmissions

#### Input Parameters
* `form_id` - _required_

### listHooksBySiteId

#### Input Parameters
* `site_id` - _required_

### createHookBySiteId

#### Input Parameters
* `site_id` - _required_

### listHookTypes

### deleteHookBySiteId

#### Input Parameters
* `hook_id` - _required_

### getHook

#### Input Parameters
* `hook_id` - _required_

### updateHook

#### Input Parameters
* `hook_id` - _required_

### enableHook

#### Input Parameters
* `hook_id` - _required_

### createTicket

#### Input Parameters
* `client_id` - _required_

### showTicket

#### Input Parameters
* `ticket_id` - _required_

### exchangeTicket

#### Input Parameters
* `ticket_id` - _required_

### listSites

#### Input Parameters
* `name` - _optional_
* `filter` - _optional_
    Possible values: all, owner, guest.

### createSite

#### Input Parameters
* `configure_dns` - _optional_

### deleteSite

#### Input Parameters
* `site_id` - _required_

### getSite

#### Input Parameters
* `site_id` - _required_

### updateSite

#### Input Parameters
* `site_id` - _required_

### listSiteAssets

#### Input Parameters
* `site_id` - _required_

### createSiteAsset

#### Input Parameters
* `name` - _required_
* `size` - _required_
* `content_type` - _required_
* `visibility` - _optional_

### deleteSiteAsset

#### Input Parameters
* `site_id` - _required_
* `asset_id` - _required_

### getSiteAssetInfo

#### Input Parameters
* `site_id` - _required_
* `asset_id` - _required_

### updateSiteAsset

#### Input Parameters
* `state` - _required_
* `asset_id` - _required_

### getSiteAssetPublicSignature

#### Input Parameters
* `site_id` - _required_
* `asset_id` - _required_

### listSiteBuildHooks

#### Input Parameters
* `site_id` - _required_

### createSiteBuildHook

#### Input Parameters
* `site_id` - _required_

### deleteSiteBuildHook

#### Input Parameters
* `site_id` - _required_
* `id` - _required_

### getSiteBuildHook

#### Input Parameters
* `site_id` - _required_
* `id` - _required_

### updateSiteBuildHook

#### Input Parameters
* `site_id` - _required_
* `id` - _required_

### listSiteBuilds

#### Input Parameters
* `site_id` - _required_

### listSiteDeployedBranches

#### Input Parameters
* `site_id` - _required_

### listSiteDeploys

#### Input Parameters
* `site_id` - _required_

### createSiteDeploy

#### Input Parameters
* `title` - _optional_

### getSiteDeploy

#### Input Parameters
* `site_id` - _required_
* `deploy_id` - _required_

### updateSiteDeploy

#### Input Parameters
* `site_id` - _required_
* `deploy_id` - _required_

### restoreSiteDeploy

#### Input Parameters
* `site_id` - _required_
* `deploy_id` - _required_

### getDNSForSite

#### Input Parameters
* `site_id` - _required_

### configureDNSForSite

#### Input Parameters
* `site_id` - _required_

### listSiteFiles

#### Input Parameters
* `site_id` - _required_

### getSiteFileByPathName

#### Input Parameters
* `site_id` - _required_
* `file_path` - _required_

### listSiteForms

#### Input Parameters
* `site_id` - _required_

### getSiteMetadata

#### Input Parameters
* `site_id` - _required_

### updateSiteMetadata

#### Input Parameters
* `site_id` - _required_

### listSiteSnippets

#### Input Parameters
* `site_id` - _required_

### createSiteSnippet

#### Input Parameters
* `site_id` - _required_

### deleteSiteSnippet

#### Input Parameters
* `site_id` - _required_
* `snippet_id` - _required_

### getSiteSnippet

#### Input Parameters
* `site_id` - _required_
* `snippet_id` - _required_

### updateSiteSnippet

#### Input Parameters
* `site_id` - _required_
* `snippet_id` - _required_

### showSiteTLSCertificate

#### Input Parameters
* `site_id` - _required_

### provisionSiteTLSCertificate

#### Input Parameters
* `site_id` - _required_
* `certificate` - _optional_
* `key` - _optional_
* `ca_certificates` - _optional_

### listSiteSubmissions

#### Input Parameters
* `site_id` - _required_

### deleteSubmission

#### Input Parameters
* `submission_id` - _required_

### listFormSubmission

#### Input Parameters
* `query` - _optional_

### listMembersForAccount

#### Input Parameters
* `account_slug` - _required_

### addMemberToAccount

#### Input Parameters
* `role` - _optional_
    Possible values: Owner, Collaborator, Controller.
* `email` - _required_

### listSitesForAccount

#### Input Parameters
* `name` - _optional_
* `account_slug` - _required_

### createSiteInTeam

#### Input Parameters
* `configure_dns` - _optional_
* `account_slug` - _required_

## License

**flow**ground :- Telekom iPaaS / netlify-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
