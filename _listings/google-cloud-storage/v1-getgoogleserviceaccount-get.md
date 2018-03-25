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
  /v1:getGoogleServiceAccount:
    get:
      summary: Get Service Account
      description: Returns the Google service account that is used by Storage Transfer
        Service to access buckets in the project where transfers run or in other projects
      operationId: storagetransfer.getGoogleServiceAccount
      parameters:
      - in: query
        name: projectId
        description: The ID of the Google Developers Console project that the Google
          service account is associated with
      responses:
        200:
          description: OK
      tags:
      - account
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