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
  /b:
    get:
      summary: Get Buckets
      description: Retrieves a list of buckets for a given project
      operationId: storage.buckets.list
      parameters:
      - in: query
        name: maxResults
        description: Maximum number of buckets to return in a single response
      - in: query
        name: pageToken
        description: A previously-returned page token representing part of the larger
          set of results to view
      - in: query
        name: prefix
        description: Filter results to buckets whose names begin with this prefix
      - in: query
        name: project
        description: A valid API project identifier
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