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
    delete:
      summary: Delete Bucket
      description: Permanently deletes an empty bucket
      operationId: storage.buckets.delete
      parameters:
      - in: path
        name: bucket
        description: Name of a bucket
      - in: query
        name: ifMetagenerationMatch
        description: If set, only deletes the bucket if its metageneration matches
          this value
      - in: query
        name: ifMetagenerationNotMatch
        description: If set, only deletes the bucket if its metageneration does not
          match this value
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