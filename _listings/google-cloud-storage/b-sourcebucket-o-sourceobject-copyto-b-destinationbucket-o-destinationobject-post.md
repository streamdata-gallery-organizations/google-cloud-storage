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
  /b/{sourceBucket}/o/{sourceObject}/copyTo/b/{destinationBucket}/o/{destinationObject}:
    post:
      summary: Copy Object
      description: Copies a source object to a destination object
      operationId: storage.objects.copy
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
        description: Makes the operation conditional on whether the destination object's
          current generation matches the given value
      - in: query
        name: ifGenerationNotMatch
        description: Makes the operation conditional on whether the destination object's
          current generation does not match the given value
      - in: query
        name: ifMetagenerationMatch
        description: Makes the operation conditional on whether the destination object's
          current metageneration matches the given value
      - in: query
        name: ifMetagenerationNotMatch
        description: Makes the operation conditional on whether the destination object's
          current metageneration does not match the given value
      - in: query
        name: ifSourceGenerationMatch
        description: Makes the operation conditional on whether the source object's
          generation matches the given value
      - in: query
        name: ifSourceGenerationNotMatch
        description: Makes the operation conditional on whether the source object's
          generation does not match the given value
      - in: query
        name: ifSourceMetagenerationMatch
        description: Makes the operation conditional on whether the source object's
          current metageneration matches the given value
      - in: query
        name: ifSourceMetagenerationNotMatch
        description: Makes the operation conditional on whether the source object's
          current metageneration does not match the given value
      - in: query
        name: projection
        description: Set of properties to return
      - in: path
        name: sourceBucket
        description: Name of the bucket in which to find the source object
      - in: query
        name: sourceGeneration
        description: If present, selects a specific revision of the source object
          (as opposed to the latest version, the default)
      - in: path
        name: sourceObject
        description: Name of the source object
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