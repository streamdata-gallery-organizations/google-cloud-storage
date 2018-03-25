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
  /b/{destinationBucket}/o/{destinationObject}/compose:
    post:
      summary: Concatenate Objects
      description: Concatenates a list of existing objects into a new object in the
        same bucket
      operationId: storage.objects.compose
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: destinationBucket
        description: Name of the bucket in which to store the new object
      - in: path
        name: destinationObject
        description: Name of the new object
      - in: query
        name: destinationPredefinedAcl
        description: Apply a predefined set of access controls to the destination
          object
      - in: query
        name: ifGenerationMatch
        description: Makes the operation conditional on whether the object's current
          generation matches the given value
      - in: query
        name: ifMetagenerationMatch
        description: Makes the operation conditional on whether the object's current
          metageneration matches the given value
      responses:
        200:
          description: OK
      tags:
      - object
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