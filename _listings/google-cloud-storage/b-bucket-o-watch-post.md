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
  /b/{bucket}/o/watch:
    post:
      summary: Update Object
      description: Watch for changes on all objects in a bucket
      operationId: storage.objects.watchAll
      parameters:
      - in: path
        name: bucket
        description: Name of the bucket in which to look for objects
      - in: query
        name: delimiter
        description: Returns results in a directory-like mode
      - in: query
        name: maxResults
        description: Maximum number of items plus prefixes to return in a single page
          of responses
      - in: query
        name: pageToken
        description: A previously-returned page token representing part of the larger
          set of results to view
      - in: query
        name: prefix
        description: Filter results to objects whose names begin with this prefix
      - in: query
        name: projection
        description: Set of properties to return
      - in: body
        name: resource
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: versions
        description: If true, lists all versions of an object as distinct results
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