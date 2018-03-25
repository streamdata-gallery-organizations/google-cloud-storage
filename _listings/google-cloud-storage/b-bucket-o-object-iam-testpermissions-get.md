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
  /b/{bucket}/o/{object}/iam/testPermissions:
    get:
      summary: Test Object IAM Permissions
      description: Tests a set of permissions on the given object to see which, if
        any, are held by the caller
      operationId: storage.objects.testIamPermissions
      parameters:
      - in: path
        name: bucket
        description: Name of the bucket in which the object resides
      - in: query
        name: generation
        description: If present, selects a specific revision of this object (as opposed
          to the latest version, the default)
      - in: path
        name: object
        description: Name of the object
      - in: query
        name: permissions
        description: Permissions to test
      responses:
        200:
          description: OK
      tags:
      - object iam
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