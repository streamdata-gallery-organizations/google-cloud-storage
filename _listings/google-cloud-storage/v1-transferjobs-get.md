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
  /v1/transferJobs:
    get:
      summary: Get Transfer Jobs
      description: Lists transfer jobs
      operationId: storagetransfer.transferJobs.list
      parameters:
      - in: query
        name: filter
        description: A list of query parameters specified as JSON text in the form
          of {"`project_id`":"my_project_id", "`job_names`":["jobid1","jobid2",
      - in: query
        name: pageSize
        description: The list page size
      - in: query
        name: pageToken
        description: The list page token
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