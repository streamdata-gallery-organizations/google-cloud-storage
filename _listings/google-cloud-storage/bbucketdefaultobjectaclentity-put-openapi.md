---
swagger: "2.0"
x-collection-name: Google Cloud Storage
x-complete: 0
info:
  title: Google Cloud Storage Update Bucket Default ACL
  version: 1.0.0
  description: Updates a default object ACL entry on the specified bucket.
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
  /b/{bucket}/acl:
    get:
      summary: Get Bucket ACLs
      description: Retrieves ACL entries on the specified bucket.
      operationId: storage.bucketAccessControls.list
      x-api-path-slug: bbucketacl-get
      parameters:
      - in: path
        name: bucket
        description: Name of a bucket
      responses:
        200:
          description: OK
      tags:
      - Bucket ACL
    post:
      summary: Create Bucket ACL
      description: Creates a new ACL entry on the specified bucket.
      operationId: storage.bucketAccessControls.insert
      x-api-path-slug: bbucketacl-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: bucket
        description: Name of a bucket
      responses:
        200:
          description: OK
      tags:
      - Bucket ACL
  /b/{bucket}/acl/{entity}:
    delete:
      summary: Delete Bucket ACL
      description: Permanently deletes the ACL entry for the specified entity on the
        specified bucket.
      operationId: storage.bucketAccessControls.delete
      x-api-path-slug: bbucketaclentity-delete
      parameters:
      - in: path
        name: bucket
        description: Name of a bucket
      - in: path
        name: entity
        description: The entity holding the permission
      responses:
        200:
          description: OK
      tags:
      - Bucket ACL
    get:
      summary: Get Bucket ACL
      description: Returns the ACL entry for the specified entity on the specified
        bucket.
      operationId: storage.bucketAccessControls.get
      x-api-path-slug: bbucketaclentity-get
      parameters:
      - in: path
        name: bucket
        description: Name of a bucket
      - in: path
        name: entity
        description: The entity holding the permission
      responses:
        200:
          description: OK
      tags:
      - Bucket ACL
    patch:
      summary: Update Bucket ACL
      description: Updates an ACL entry on the specified bucket. This method supports
        patch semantics.
      operationId: storage.bucketAccessControls.patch
      x-api-path-slug: bbucketaclentity-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: bucket
        description: Name of a bucket
      - in: path
        name: entity
        description: The entity holding the permission
      responses:
        200:
          description: OK
      tags:
      - Bucket ACL
    put:
      summary: Update Bucket ACL
      description: Updates an ACL entry on the specified bucket.
      operationId: storage.bucketAccessControls.update
      x-api-path-slug: bbucketaclentity-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: bucket
        description: Name of a bucket
      - in: path
        name: entity
        description: The entity holding the permission
      responses:
        200:
          description: OK
      tags:
      - Bucket ACL
  /b/{bucket}/defaultObjectAcl:
    get:
      summary: Get Bucket Default ACL
      description: Retrieves default object ACL entries on the specified bucket.
      operationId: storage.defaultObjectAccessControls.list
      x-api-path-slug: bbucketdefaultobjectacl-get
      parameters:
      - in: path
        name: bucket
        description: Name of a bucket
      - in: query
        name: ifMetagenerationMatch
        description: If present, only return default ACL listing if the buckets current
          metageneration matches this value
      - in: query
        name: ifMetagenerationNotMatch
        description: If present, only return default ACL listing if the buckets current
          metageneration does not match the given value
      responses:
        200:
          description: OK
      tags:
      - Bucket ACL
    post:
      summary: Create Bucket Default ACL
      description: Creates a new default object ACL entry on the specified bucket.
      operationId: storage.defaultObjectAccessControls.insert
      x-api-path-slug: bbucketdefaultobjectacl-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: bucket
        description: Name of a bucket
      responses:
        200:
          description: OK
      tags:
      - Bucket ACL
  /b/{bucket}/defaultObjectAcl/{entity}:
    delete:
      summary: Default Bucket Default ACL
      description: Permanently deletes the default object ACL entry for the specified
        entity on the specified bucket.
      operationId: storage.defaultObjectAccessControls.delete
      x-api-path-slug: bbucketdefaultobjectaclentity-delete
      parameters:
      - in: path
        name: bucket
        description: Name of a bucket
      - in: path
        name: entity
        description: The entity holding the permission
      responses:
        200:
          description: OK
      tags:
      - Bucket ACL
    get:
      summary: Get Bucket Default ACL
      description: Returns the default object ACL entry for the specified entity on
        the specified bucket.
      operationId: storage.defaultObjectAccessControls.get
      x-api-path-slug: bbucketdefaultobjectaclentity-get
      parameters:
      - in: path
        name: bucket
        description: Name of a bucket
      - in: path
        name: entity
        description: The entity holding the permission
      responses:
        200:
          description: OK
      tags:
      - Bucket ACL
    patch:
      summary: Update Bucket Default ACL
      description: Updates a default object ACL entry on the specified bucket. This
        method supports patch semantics.
      operationId: storage.defaultObjectAccessControls.patch
      x-api-path-slug: bbucketdefaultobjectaclentity-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: bucket
        description: Name of a bucket
      - in: path
        name: entity
        description: The entity holding the permission
      responses:
        200:
          description: OK
      tags:
      - Bucket ACL
    put:
      summary: Update Bucket Default ACL
      description: Updates a default object ACL entry on the specified bucket.
      operationId: storage.defaultObjectAccessControls.update
      x-api-path-slug: bbucketdefaultobjectaclentity-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: bucket
        description: Name of a bucket
      - in: path
        name: entity
        description: The entity holding the permission
      responses:
        200:
          description: OK
      tags:
      - Bucket ACL
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