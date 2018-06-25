---
name: Watchful
x-slug: watchful
description: Watchful resulted from the need for a single, unified dashboard to easily
  monitor all of the web sites in our portfolios. After years of evolution, our solution
  has matured into a simple, complete and professional service.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
x-kinRank: "8"
x-alexaRank: "0"
tags: Watchful
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/apis.md
specificationVersion: "0.14"
apis:
- name: Watchful Get A List Of Audits
  x-api-slug: watchful
  description: Returns a list of audits
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//audits
  tags: Audits
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/audits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/audits-get-openapi.md
- name: Watchful Get The List Of Fields
  x-api-slug: watchful
  description: Returns a list of fields
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//audits/metadata
  tags: Audits,Metadata
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/auditsmetadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/auditsmetadata-get-openapi.md
- name: Watchful Delete A Specific Audit
  x-api-slug: watchful
  description: Delete a specific audit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//audits/{id}
  tags: Audits,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/auditsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/auditsid-delete-openapi.md
- name: Watchful Find Audit By ID
  x-api-slug: watchful
  description: Returns a audit based on ID
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//audits/{id}
  tags: Audits,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/auditsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/auditsid-get-openapi.md
- name: Watchful Get A List Extensions
  x-api-slug: watchful
  description: Returns a list Extensions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//extensions
  tags: Extensions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/extensions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/extensions-get-openapi.md
- name: Watchful Get The List Of Fields
  x-api-slug: watchful
  description: Returns a list of fields
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//extensions/metadata
  tags: Extensions,Metadata
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/extensionsmetadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/extensionsmetadata-get-openapi.md
- name: Watchful Set 'ignore Updates' For A Given Extension / Site_id
  x-api-slug: watchful
  description: Set 'ignore updates' for a given extension / site_id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//extensions/{id}/ignore
  tags: Extensions,Id,Ignore
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/extensionsidignore-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/extensionsidignore-post-openapi.md
- name: Watchful Remove 'ignore Updates' For A Given Extension
  x-api-slug: watchful
  description: Remove 'ignore updates' for a given extension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//extensions/{id}/unignore
  tags: Extensions,Id,Unignore
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/extensionsidunignore-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/extensionsidunignore-post-openapi.md
- name: Watchful Update The Extension On The Remote Site
  x-api-slug: watchful
  description: Update the extension on the remote site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//extensions/{id}/update
  tags: Extensions,Id,Update
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/extensionsidupdate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/extensionsidupdate-post-openapi.md
- name: Watchful Get Feedbacks
  x-api-slug: watchful
  description: Returns a list of feedbacks
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//feedbacks
  tags: Feedbacks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/feedbacks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/feedbacks-get-openapi.md
- name: Watchful Create A Feedback
  x-api-slug: watchful
  description: Create a feedback
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//feedbacks
  tags: Feedbacks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/feedbacks-post-openapi.md
- name: Watchful Get The List Of Fields
  x-api-slug: watchful
  description: Returns a list of fields
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//feedbacks/metadata
  tags: Feedbacks,Metadata
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/feedbacksmetadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/feedbacksmetadata-get-openapi.md
- name: Watchful Get A List Of Logs
  x-api-slug: watchful
  description: Returns a list of logs
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//logs
  tags: Logs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/logs-get-openapi.md
- name: Watchful Get A CSV Or PDF File Contain The List Of Logs
  x-api-slug: watchful
  description: Returns a file contain the list of logs
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//logs/export
  tags: Logs,Export
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/logsexport-get-openapi.md
- name: Watchful Get The List Of Fields
  x-api-slug: watchful
  description: Returns a list of fields
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//logs/metadata
  tags: Logs,Metadata
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/logsmetadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/logsmetadata-get-openapi.md
- name: Watchful Get The List Of Log Types
  x-api-slug: watchful
  description: Returns a list of log types
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//logs/types
  tags: Logs,Types
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/logstypes-get-openapi.md
- name: Watchful Delete A Specific Log
  x-api-slug: watchful
  description: Delete a specific log
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//logs/{id}
  tags: Logs,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/logsid-delete-openapi.md
- name: 'Watchful '
  x-api-slug: watchful
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//packages
  tags: Packages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/packages-post-openapi.md
- name: Watchful Returns A PDF Report For A Specific Site
  x-api-slug: watchful
  description: Returns a PDF report based on a site ID
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//reports/sites/{id}
  tags: Reports,Sites,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/reportssitesid-get-openapi.md
- name: Watchful Find Sites By ID
  x-api-slug: watchful
  description: Returns a report based on a site ID
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//reports/tags/{id}
  tags: Reports,Tags,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/reportstagsid-get-openapi.md
- name: Watchful Get A List Of Sites
  x-api-slug: watchful
  description: Returns a list of Sites
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites
  tags: Sites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sites-get-openapi.md
- name: Watchful Create A Site
  x-api-slug: watchful
  description: Create a site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites
  tags: Sites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sites-post-openapi.md
- name: Watchful Get The List Of Fields
  x-api-slug: watchful
  description: Returns a list of fields
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/metadata
  tags: Sites,Metadata
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesmetadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesmetadata-get-openapi.md
- name: Watchful Delete A Specific Site
  x-api-slug: watchful
  description: Delete a specific Site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}
  tags: Sites,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesid-delete-openapi.md
- name: Watchful Find Sites By ID
  x-api-slug: watchful
  description: Return a site based on ID
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}
  tags: Sites,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesid-get-openapi.md
- name: Watchful Update A Site
  x-api-slug: watchful
  description: Update a site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}
  tags: Sites,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesid-put-openapi.md
- name: Watchful Return Audits For A Specific Website
  x-api-slug: watchful
  description: Return audits for a specific website
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/audits
  tags: Sites,Id,Audits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidaudits-get-openapi.md
- name: Watchful Create An Audit For The Site
  x-api-slug: watchful
  description: Create an audit for the site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/audits
  tags: Sites,Id,Audits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidaudits-post-openapi.md
- name: Watchful Add The Site To The Backup Queue
  x-api-slug: watchful
  description: Add the site to the backup queue
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/backupnow
  tags: Sites,Id,Backupnow
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidbackupnow-post-openapi.md
- name: Watchful Return Backup Profile
  x-api-slug: watchful
  description: Return backup profile
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/backupprofiles
  tags: Sites,Id,Backupprofiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidbackupprofiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidbackupprofiles-get-openapi.md
- name: Watchful List Of Latest Backups
  x-api-slug: watchful
  description: List of latest backups
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/backups
  tags: Sites,Id,Backups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidbackups-get-openapi.md
- name: Watchful Start A Remote Backup For The Site
  x-api-slug: watchful
  description: Start a remote backup for the site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/backupstart
  tags: Sites,Id,Backupstart
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidbackupstart-post-openapi.md
- name: Watchful Step (continue) A Remote Backup For The Site
  x-api-slug: watchful
  description: Step (continue) a remote backup for the site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/backupstep
  tags: Sites,Id,Backupstep
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidbackupstep-post-openapi.md
- name: Watchful Get Extensions For A Site
  x-api-slug: watchful
  description: Get extensions for a site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/extensions
  tags: Sites,Id,Extensions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidextensions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidextensions-get-openapi.md
- name: Watchful Install Extension
  x-api-slug: watchful
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/extensions
  tags: Sites,Id,Extensions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidextensions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidextensions-post-openapi.md
- name: Watchful Return Logs For A Specific Website
  x-api-slug: watchful
  description: Return logs for a specific website
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/logs
  tags: Sites,Id,Logs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidlogs-get-openapi.md
- name: Watchful Create A Custom Log For A Specific Website
  x-api-slug: watchful
  description: Create a custom log for a specific website
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/logs
  tags: Sites,Id,Logs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidlogs-post-openapi.md
- name: Watchful Delete Uptime Monitor
  x-api-slug: watchful
  description: Return boolean
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/monitor
  tags: Sites,Id,Monitor
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidmonitor-delete-openapi.md
- name: Watchful Post Uptime Monitor
  x-api-slug: watchful
  description: Return boolean
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/monitor
  tags: Sites,Id,Monitor
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidmonitor-post-openapi.md
- name: Watchful Scan The Site For Malware
  x-api-slug: watchful
  description: Scan the site for malware
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/scanner
  tags: Sites,Id,Scanner
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidscanner-get-openapi.md
- name: Watchful SEO Analyze For A Page
  x-api-slug: watchful
  description: SEO analyze for a page
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/seo
  tags: Sites,Id,Seo
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidseo-get-openapi.md
- name: Watchful Return Tags For A Specific Website
  x-api-slug: watchful
  description: Return tags for a specific website
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/tags
  tags: Sites,Id,Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidtags-get-openapi.md
- name: Watchful Add Tags For A Specific Website
  x-api-slug: watchful
  description: Add tags for a specific website
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/tags
  tags: Sites,Id,Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidtags-post-openapi.md
- name: Watchful Update Joomla Core On The Remote Site
  x-api-slug: watchful
  description: Update Joomla core on the remote site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/updatejoomla
  tags: Sites,Id,Updatejoomla
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidupdatejoomla-post-openapi.md
- name: Watchful Return Uptime Data
  x-api-slug: watchful
  description: Return uptime data
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/uptime
  tags: Sites,Id,Uptime
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesiduptime-get-openapi.md
- name: Watchful Validate The Site, Return The New Logs
  x-api-slug: watchful
  description: validate the site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/validate
  tags: Sites,Id,Validate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidvalidate-get-openapi.md
- name: Watchful Validate The Site, Return The Debug Information
  x-api-slug: watchful
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/validatedebug
  tags: Sites,Id,Validatedebug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/sitesidvalidatedebug-get-openapi.md
- name: Watchful Get A List Of SSO Users
  x-api-slug: watchful
  description: Returns a list of SSO Users
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//ssousers
  tags: Ssousers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/ssousers-get-openapi.md
- name: Watchful Create A SSO User
  x-api-slug: watchful
  description: Create a SSO User
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//ssousers
  tags: Ssousers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/ssousers-post-openapi.md
- name: Watchful Delete A Specific SSO User
  x-api-slug: watchful
  description: Delete a specific SSO User
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//ssousers/{id}
  tags: Ssousers,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/ssousersid-delete-openapi.md
- name: Watchful Find SSO User By ID
  x-api-slug: watchful
  description: Returns a SSO User based on ID
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//ssousers/{id}
  tags: Ssousers,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/ssousersid-get-openapi.md
- name: Watchful Update A SSO User
  x-api-slug: watchful
  description: Update a SSO User
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//ssousers/{id}
  tags: Ssousers,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/ssousersid-put-openapi.md
- name: Watchful Get A List Of Tags
  x-api-slug: watchful
  description: Returns a list of tags
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//tags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/tags-get-openapi.md
- name: Watchful Create A Tag
  x-api-slug: watchful
  description: Create a tag
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//tags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/tags-post-openapi.md
- name: Watchful Get The List Of Fields
  x-api-slug: watchful
  description: Returns a list of fields
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//tags/metadata
  tags: Tags,Metadata
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/tagsmetadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/tagsmetadata-get-openapi.md
- name: Watchful Delete A Specific Tag
  x-api-slug: watchful
  description: Delete a specific tag
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//tags/{id}
  tags: Tags,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/tagsid-delete-openapi.md
- name: Watchful Find Tag By ID
  x-api-slug: watchful
  description: Returns a tag based on ID
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//tags/{id}
  tags: Tags,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/tagsid-get-openapi.md
- name: Watchful Update A Tag
  x-api-slug: watchful
  description: Update a tag
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//tags/{id}
  tags: Tags,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/tagsid-put-openapi.md
- name: Watchful Find Sites By Tag ID
  x-api-slug: watchful
  description: Returns a list of sites based with a specific tag id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//tags/{id}/sites
  tags: Tags,Id,Sites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/tagsidsites-get-openapi.md
- name: Watchful Create A Audit
  x-api-slug: watchful
  description: Create a audit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//audits
  tags: Audits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/audits-post-openapi.md
- name: Watchful Get List Of Versions
  x-api-slug: watchful
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//versions
  tags: Versions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/versions-get-openapi.md
- name: Watchful Find A Version By ID
  x-api-slug: watchful
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//versions/{id}
  tags: Versions,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/versionsid-get-openapi.md
- name: Watchful
  x-api-slug: watchful
  description: Watchful resulted from the need for a single, unified dashboard to
    easily monitor all of the web sites in our portfolios. After years of evolution,
    our solution has matured into a simple, complete and professional service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1
  tags: Watchful
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/watchful/master/_listings/watchful/openapi.md
x-common:
- type: x-application-gallery
  url: https://watchful.li/apps/
- type: x-blog
  url: https://watchful.li/news/
- type: x-blog-rss
  url: https://watchful.li/news/feed/rss.html
- type: x-developer
  url: https://watchful.li/support-services/kb/article/watchful-rest-api
- type: x-facebook
  url: https://www.facebook.com/watchfulli
- type: x-faq
  url: https://watchful.li/support-services/faq.html
- type: x-google-plus
  url: https://plus.google.com/+WatchfulLi
- type: x-knowledgebase
  url: https://watchful.li/support-services/kb.html
- type: x-pricing
  url: https://watchful.li/pricing
- type: x-privacy
  url: https://watchful.li/privacy-policy.html
- type: x-terms-of-service
  url: https://watchful.li/terms-of-service.html
- type: x-twitter
  url: https://twitter.com/watchfulli
- type: x-website
  url: http://watchful.li
- type: x-website
  url: https://watchful.li/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---