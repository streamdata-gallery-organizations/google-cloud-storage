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
  /v1/{jobName}:
    get:
      summary: Get Transfer Jobs
      description: Gets a transfer job
      operationId: storagetransfer.transferJobs.get
      parameters:
      - in: path
        name: jobName
        description: The job to get
      - in: query
        name: projectId
        description: The ID of the Google Developers Console project that owns the
          job
      responses:
        200:
          description: OK
      tags:
      - job
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