---
swagger: "2.0"
x-collection-name: Google Cloud Storage
x-complete: 0
info:
  title: Google Cloud Storage Update bucket
  version: 1.0.0
  description: Updates a bucket. Changes to the bucket will be readable immediately
    after writing, but configuration changes may take time to propagate.
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
      description: Retrieves a list of buckets for a given project.
      operationId: storage.buckets.list
      x-api-path-slug: b-get
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
      - Bucket
    post:
      summary: Create Bucket
      description: Creates a new bucket.
      operationId: storage.buckets.insert
      x-api-path-slug: b-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: predefinedAcl
        description: Apply a predefined set of access controls to this bucket
      - in: query
        name: predefinedDefaultObjectAcl
        description: Apply a predefined set of default object access controls to this
          bucket
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
      - Bucket
  /b/{bucket}:
    delete:
      summary: Delete Bucket
      description: Permanently deletes an empty bucket.
      operationId: storage.buckets.delete
      x-api-path-slug: bbucket-delete
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
      - Bucket
    get:
      summary: Get Bucket
      description: Returns metadata for the specified bucket.
      operationId: storage.buckets.get
      x-api-path-slug: bbucket-get
      parameters:
      - in: path
        name: bucket
        description: Name of a bucket
      - in: query
        name: ifMetagenerationMatch
        description: Makes the return of the bucket metadata conditional on whether
          the buckets current metageneration matches the given value
      - in: query
        name: ifMetagenerationNotMatch
        description: Makes the return of the bucket metadata conditional on whether
          the buckets current metageneration does not match the given value
      - in: query
        name: projection
        description: Set of properties to return
      responses:
        200:
          description: OK
      tags:
      - Bucket
    patch:
      summary: Update bucket
      description: Updates a bucket. Changes to the bucket will be readable immediately
        after writing, but configuration changes may take time to propagate. This
        method supports patch semantics.
      operationId: storage.buckets.patch
      x-api-path-slug: bbucket-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: bucket
        description: Name of a bucket
      - in: query
        name: ifMetagenerationMatch
        description: Makes the return of the bucket metadata conditional on whether
          the buckets current metageneration matches the given value
      - in: query
        name: ifMetagenerationNotMatch
        description: Makes the return of the bucket metadata conditional on whether
          the buckets current metageneration does not match the given value
      - in: query
        name: predefinedAcl
        description: Apply a predefined set of access controls to this bucket
      - in: query
        name: predefinedDefaultObjectAcl
        description: Apply a predefined set of default object access controls to this
          bucket
      - in: query
        name: projection
        description: Set of properties to return
      responses:
        200:
          description: OK
      tags:
      - Bucket
    put:
      summary: Update bucket
      description: Updates a bucket. Changes to the bucket will be readable immediately
        after writing, but configuration changes may take time to propagate.
      operationId: storage.buckets.update
      x-api-path-slug: bbucket-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: bucket
        description: Name of a bucket
      - in: query
        name: ifMetagenerationMatch
        description: Makes the return of the bucket metadata conditional on whether
          the buckets current metageneration matches the given value
      - in: query
        name: ifMetagenerationNotMatch
        description: Makes the return of the bucket metadata conditional on whether
          the buckets current metageneration does not match the given value
      - in: query
        name: predefinedAcl
        description: Apply a predefined set of access controls to this bucket
      - in: query
        name: predefinedDefaultObjectAcl
        description: Apply a predefined set of default object access controls to this
          bucket
      - in: query
        name: projection
        description: Set of properties to return
      responses:
        200:
          description: OK
      tags:
      - Bucket
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