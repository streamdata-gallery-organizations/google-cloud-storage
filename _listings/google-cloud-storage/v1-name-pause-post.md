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
  /v1/{name}:pause:
    post:
      summary: Pause Transfer Operation
      description: Pauses a transfer operation
      operationId: storagetransfer.transferOperations.pause
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The name of the transfer operation
      responses:
        200:
          description: OK
      tags:
      - operation
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