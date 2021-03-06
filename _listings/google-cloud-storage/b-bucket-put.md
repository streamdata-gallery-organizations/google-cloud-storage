---
swagger: "2.0"
info:
  title: Google Cloud Storage
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /b/{bucket}:
    put:
      summary: Update bucket
      description: Updates a bucket
      operationId: storage.buckets.update
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: bucket
        description: Name of a bucket
      - in: query
        name: ifMetagenerationMatch
        description: Makes the return of the bucket metadata conditional on whether
          the bucket's current metageneration matches the given value
      - in: query
        name: ifMetagenerationNotMatch
        description: Makes the return of the bucket metadata conditional on whether
          the bucket's current metageneration does not match the given value
      - in: query
        name: predefinedAcl
        description: Apply a predefined set of access controls to this bucket
      - in: query
        name: predefinedDefaultObjectAcl
        description: Apply a predefined set of default object access controls to this
          bucket
      - in: query
        name: projection
        description: Set of properties to return
      responses:
        200:
          description: OK
      tags:
      - bucket
definitions: []
x-collection-name: Google Cloud Storage
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