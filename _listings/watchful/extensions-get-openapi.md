---
swagger: "2.0"
x-collection-name: Watchful
x-complete: 0
info:
  title: Watchful Get A List Extensions
  description: Returns a list Extensions
  version: 1.0.0
host: watchful.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /audits:
    get:
      summary: Get A List Of Audits
      description: Returns a list of audits
      operationId: getAudits
      x-api-path-slug: audits-get
      parameters:
      - in: query
        name: limit
        description: Number of object to return (max 100, default 25)
      - in: query
        name: limitstart
        description: Start of the return (default 0)
      - in: query
        name: order
        description: ORDER by this field separete by comas
      responses:
        200:
          description: OK
      tags:
      - Audits
  /audits/metadata:
    get:
      summary: Get The List Of Fields
      description: Returns a list of fields
      operationId: getFieldsAudits
      x-api-path-slug: auditsmetadata-get
      responses:
        200:
          description: OK
      tags:
      - Audits
      - Metadata
  /audits/{id}:
    delete:
      summary: Delete A Specific Audit
      description: Delete a specific audit.
      operationId: deleteAuditById
      x-api-path-slug: auditsid-delete
      parameters:
      - in: path
        name: id
        description: ID of audit that needs to be deleted
      responses:
        200:
          description: OK
      tags:
      - Audits
      - Id
    get:
      summary: Find Audit By ID
      description: Returns a audit based on ID
      operationId: getAuditById
      x-api-path-slug: auditsid-get
      parameters:
      - in: query
        name: fields
        description: 'Fields to return separate by comas: name,id'
      - in: path
        name: id
        description: ID of audit that needs to be fetched
      responses:
        200:
          description: OK
      tags:
      - Audits
      - Id
  /extensions:
    get:
      summary: Get A List Extensions
      description: Returns a list Extensions
      operationId: getExtensions
      x-api-path-slug: extensions-get
      parameters:
      - in: query
        name: ext_name
        description: Do a LIKE search, you can also use %
      - in: query
        name: ext_prefix
        description: Do a LIKE search, you can also use %
      - in: query
        name: fields
        description: 'Fields to return separate by comas: name,id'
      - in: query
        name: limit
        description: Number of object to return (max 100, default 25)
      - in: query
        name: limitstart
        description: Start of the return (default 0)
      - in: query
        name: order
        description: ORDER by this field separete by comas
      - in: query
        name: siteids
        description: List of sites id separated by comma
      - in: query
        name: version
        description: Do a LIKE search, you can also use %
      - in: query
        name: vUpdate
        description: update available for this extension
      responses:
        200:
          description: OK
      tags:
      - Extensions
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---