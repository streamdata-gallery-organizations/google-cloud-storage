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
  /b/{bucket}/o:
    post:
      summary: Add New Object
      description: Stores a new object and metadata
      operationId: storage.objects.insert
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: bucket
        description: Name of the bucket in which to store the new object
      - in: query
        name: contentEncoding
        description: If set, sets the contentEncoding property of the final object
          to this value
      - in: query
        name: ifGenerationMatch
        description: Makes the operation conditional on whether the object's current
          generation matches the given value
      - in: query
        name: ifGenerationNotMatch
        description: Makes the operation conditional on whether the object's current
          generation does not match the given value
      - in: query
        name: ifMetagenerationMatch
        description: Makes the operation conditional on whether the object's current
          metageneration matches the given value
      - in: query
        name: ifMetagenerationNotMatch
        description: Makes the operation conditional on whether the object's current
          metageneration does not match the given value
      - in: query
        name: name
        description: Name of the object
      - in: query
        name: predefinedAcl
        description: Apply a predefined set of access controls to this object
      - in: query
        name: projection
        description: Set of properties to return
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