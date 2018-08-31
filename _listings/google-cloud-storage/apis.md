---
name: Google Cloud Storage
x-slug: google-cloud-storage
description: Google Cloud Storage is unified object storage for developers and enterprises,
  from live data serving to data analytics/ML to data archiving. Google Cloud Storage
  allows world-wide storage and retrieval of any amount of data at any time. You can
  use Google Cloud Storage for a range of scenarios including serving website content,
  storing data for archival and disaster recovery, or distributing large data objects
  to users via direct download.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Cloud Storage
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Storage - Get Buckets
  x-api-slug: b-get
  description: Retrieves a list of buckets for a given project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/b-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/b-get-openapi.md
- name: Google Cloud Storage - Create Bucket
  x-api-slug: b-post
  description: Creates a new bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/b-post-openapi.md
- name: Google Cloud Storage - Delete Bucket
  x-api-slug: bbucket-delete
  description: Permanently deletes an empty bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucket-delete-openapi.md
- name: Google Cloud Storage - Get Bucket
  x-api-slug: bbucket-get
  description: Returns metadata for the specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucket-get-openapi.md
- name: Google Cloud Storage - Update bucket
  x-api-slug: bbucket-patch
  description: Updates a bucket. Changes to the bucket will be readable immediately
    after writing, but configuration changes may take time to propagate. This method
    supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucket-patch-openapi.md
- name: Google Cloud Storage - Update bucket
  x-api-slug: bbucket-put
  description: Updates a bucket. Changes to the bucket will be readable immediately
    after writing, but configuration changes may take time to propagate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucket-put-openapi.md
- name: Google Cloud Storage - Get Bucket ACLs
  x-api-slug: bbucketacl-get
  description: Retrieves ACL entries on the specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketacl-get-openapi.md
- name: Google Cloud Storage - Create Bucket ACL
  x-api-slug: bbucketacl-post
  description: Creates a new ACL entry on the specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketacl-post-openapi.md
- name: Google Cloud Storage - Delete Bucket ACL
  x-api-slug: bbucketaclentity-delete
  description: Permanently deletes the ACL entry for the specified entity on the specified
    bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketaclentity-delete-openapi.md
- name: Google Cloud Storage - Get Bucket ACL
  x-api-slug: bbucketaclentity-get
  description: Returns the ACL entry for the specified entity on the specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketaclentity-get-openapi.md
- name: Google Cloud Storage - Update Bucket ACL
  x-api-slug: bbucketaclentity-patch
  description: Updates an ACL entry on the specified bucket. This method supports
    patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketaclentity-patch-openapi.md
- name: Google Cloud Storage - Update Bucket ACL
  x-api-slug: bbucketaclentity-put
  description: Updates an ACL entry on the specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketaclentity-put-openapi.md
- name: Google Cloud Storage - Get Bucket Default ACL
  x-api-slug: bbucketdefaultobjectacl-get
  description: Retrieves default object ACL entries on the specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketdefaultobjectacl-get-openapi.md
- name: Google Cloud Storage - Create Bucket Default ACL
  x-api-slug: bbucketdefaultobjectacl-post
  description: Creates a new default object ACL entry on the specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketdefaultobjectacl-post-openapi.md
- name: Google Cloud Storage - Default Bucket Default ACL
  x-api-slug: bbucketdefaultobjectaclentity-delete
  description: Permanently deletes the default object ACL entry for the specified
    entity on the specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketdefaultobjectaclentity-delete-openapi.md
- name: Google Cloud Storage - Get Bucket Default ACL
  x-api-slug: bbucketdefaultobjectaclentity-get
  description: Returns the default object ACL entry for the specified entity on the
    specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketdefaultobjectaclentity-get-openapi.md
- name: Google Cloud Storage - Update Bucket Default ACL
  x-api-slug: bbucketdefaultobjectaclentity-patch
  description: Updates a default object ACL entry on the specified bucket. This method
    supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketdefaultobjectaclentity-patch-openapi.md
- name: Google Cloud Storage - Update Bucket Default ACL
  x-api-slug: bbucketdefaultobjectaclentity-put
  description: Updates a default object ACL entry on the specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketdefaultobjectaclentity-put-openapi.md
- name: Google Cloud Storage - Get Bucket IAM
  x-api-slug: bbucketiam-get
  description: Returns an IAM policy for the specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketiam-get-openapi.md
- name: Google Cloud Storage - Update Bucket IAM
  x-api-slug: bbucketiam-put
  description: Updates an IAM policy for the specified bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketiam-put-openapi.md
- name: Google Cloud Storage - Test Bucket IAM Permissions
  x-api-slug: bbucketiamtestpermissions-get
  description: Tests a set of permissions on the given bucket to see which, if any,
    are held by the caller.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketiamtestpermissions-get-openapi.md
- name: Google Cloud Storage - Get Objects
  x-api-slug: bbucketo-get
  description: Retrieves a list of objects matching the criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketo-get-openapi.md
- name: Google Cloud Storage - Add New Object
  x-api-slug: bbucketo-post
  description: Stores a new object and metadata.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketo-post-openapi.md
- name: Google Cloud Storage - Update Object
  x-api-slug: bbucketowatch-post
  description: Watch for changes on all objects in a bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketowatch-post-openapi.md
- name: Google Cloud Storage - Delete Object
  x-api-slug: bbucketoobject-delete
  description: Deletes an object and its metadata. Deletions are permanent if versioning
    is not enabled for the bucket, or if the generation parameter is used.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketoobject-delete-openapi.md
- name: Google Cloud Storage - Get Object
  x-api-slug: bbucketoobject-get
  description: Retrieves an object or its metadata.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketoobject-get-openapi.md
- name: Google Cloud Storage - Update Object
  x-api-slug: bbucketoobject-patch
  description: Updates an object's metadata. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketoobject-patch-openapi.md
- name: Google Cloud Storage - Update Object
  x-api-slug: bbucketoobject-put
  description: Updates an object's metadata.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketoobject-put-openapi.md
- name: Google Cloud Storage - Get Object ACLs
  x-api-slug: bbucketoobjectacl-get
  description: Retrieves ACL entries on the specified object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketoobjectacl-get-openapi.md
- name: Google Cloud Storage - Create Object ACL
  x-api-slug: bbucketoobjectacl-post
  description: Creates a new ACL entry on the specified object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketoobjectacl-post-openapi.md
- name: Google Cloud Storage - Delete Object ACL
  x-api-slug: bbucketoobjectaclentity-delete
  description: Permanently deletes the ACL entry for the specified entity on the specified
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketoobjectaclentity-delete-openapi.md
- name: Google Cloud Storage - Get Object ACL
  x-api-slug: bbucketoobjectaclentity-get
  description: Returns the ACL entry for the specified entity on the specified object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketoobjectaclentity-get-openapi.md
- name: Google Cloud Storage - Update Object ACL
  x-api-slug: bbucketoobjectaclentity-patch
  description: Updates an ACL entry on the specified object. This method supports
    patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketoobjectaclentity-patch-openapi.md
- name: Google Cloud Storage - Update Object ACL
  x-api-slug: bbucketoobjectaclentity-put
  description: Updates an ACL entry on the specified object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketoobjectaclentity-put-openapi.md
- name: Google Cloud Storage - Get Object IAM
  x-api-slug: bbucketoobjectiam-get
  description: Returns an IAM policy for the specified object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketoobjectiam-get-openapi.md
- name: Google Cloud Storage - Update Object IAM
  x-api-slug: bbucketoobjectiam-put
  description: Updates an IAM policy for the specified object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketoobjectiam-put-openapi.md
- name: Google Cloud Storage - Test Object IAM Permissions
  x-api-slug: bbucketoobjectiamtestpermissions-get
  description: Tests a set of permissions on the given object to see which, if any,
    are held by the caller.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bbucketoobjectiamtestpermissions-get-openapi.md
- name: Google Cloud Storage - Concatenate Objects
  x-api-slug: bdestinationbucketodestinationobjectcompose-post
  description: Concatenates a list of existing objects into a new object in the same
    bucket.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bdestinationbucketodestinationobjectcompose-post-openapi.md
- name: Google Cloud Storage - Copy Object
  x-api-slug: bsourcebucketosourceobjectcopytobdestinationbucketodestinationobject-post
  description: Copies a source object to a destination object. Optionally overrides
    metadata.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bsourcebucketosourceobjectcopytobdestinationbucketodestinationobject-post-openapi.md
- name: Google Cloud Storage - Rewrite Object
  x-api-slug: bsourcebucketosourceobjectrewritetobdestinationbucketodestinationobject-post
  description: Rewrites a source object to a destination object. Optionally overrides
    metadata.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/bsourcebucketosourceobjectrewritetobdestinationbucketodestinationobject-post-openapi.md
- name: Google Cloud Storage - Stop Watching Channel
  x-api-slug: channelsstop-post
  description: Stop watching resources through this channel
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/channelsstop-post-openapi.md
- name: Google Cloud Storage - Get Account
  x-api-slug: v1googleserviceaccountsprojectid-get
  description: Returns the Google service account that is used by Storage Transfer
    Service to access buckets in the project where transfers run or in other projects.
    Each Google service account is associated with one Google Developers Console project.
    Users should add this service account to the Google Cloud Storage bucket ACLs
    to grant access to Storage Transfer Service. This service account is created and
    owned by Storage Transfer Service and can only be used by Storage Transfer Service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/v1googleserviceaccountsprojectid-get-openapi.md
- name: Google Cloud Storage - Get Transfer Jobs
  x-api-slug: v1transferjobs-get
  description: Lists transfer jobs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/v1transferjobs-get-openapi.md
- name: Google Cloud Storage - Create Transfer Jobs
  x-api-slug: v1transferjobs-post
  description: Creates a transfer job that runs periodically.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/v1transferjobs-post-openapi.md
- name: Google Cloud Storage - Get Transfer Jobs
  x-api-slug: v1jobname-get
  description: Gets a transfer job.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/v1jobname-get-openapi.md
- name: Google Cloud Storage - Update Transfer Jobs
  x-api-slug: v1jobname-patch
  description: Updates a transfer job. Updating a job's transfer spec does not affect
    transfer operations that are running already. Updating the scheduling of a job
    is not allowed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/v1jobname-patch-openapi.md
- name: Google Cloud Storage - Delete Transfer Operations
  x-api-slug: v1name-delete
  description: This method is not supported and the server returns `UNIMPLEMENTED`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/v1name-delete-openapi.md
- name: Google Cloud Storage - Get Transfer Operations
  x-api-slug: v1name-get
  description: 'Lists operations that match the specified filter in the request. If
    the server doesn''t support this method, it returns `UNIMPLEMENTED`. NOTE: the
    `name` binding below allows API services to override the binding to use different
    resource name schemes, such as `users/*/operations`.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/v1name-get-openapi.md
- name: Google Cloud Storage - Cancel Transfer Operation
  x-api-slug: v1namecancel-post
  description: Cancels a transfer. Use the get method to check whether the cancellation
    succeeded or whether the operation completed despite cancellation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/v1namecancel-post-openapi.md
- name: Google Cloud Storage - Pause Transfer Operation
  x-api-slug: v1namepause-post
  description: Pauses a transfer operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/v1namepause-post-openapi.md
- name: Google Cloud Storage - Resume Transfer Operation
  x-api-slug: v1nameresume-post
  description: Resumes a transfer operation that is paused.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/v1nameresume-post-openapi.md
- name: Google Cloud Storage - Get Service Account
  x-api-slug: v1getgoogleserviceaccount-get
  description: Returns the Google service account that is used by Storage Transfer
    Service to access buckets in the project where transfers run or in other projects.
    Each Google service account is associated with one Google Developers Console project.
    Users should add this service account to the Google Cloud Storage bucket ACLs
    to grant access to Storage Transfer Service. This service account is created and
    owned by Storage Transfer Service and can only be used by Storage Transfer Service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-storage-unified-object-storage-2x.png
  humanURL: https://cloud.google.com/storage/
  baseURL: https:///
  tags: Google APIs, Cloud, Storage, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-storage/master/_listings/google-cloud-storage/v1getgoogleserviceaccount-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.sql.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.storage.stack.network
- type: x-authentication
  url: https://cloud.google.com/storage/docs/authentication
- type: x-best-practices
  url: https://cloud.google.com/storage/docs/best-practices
- type: x-change-log
  url: https://cloud.google.com/storage/release-notes
- type: x-code
  url: https://cloud.google.com/storage/docs/reference/libraries
- type: x-concepts
  url: https://cloud.google.com/storage/docs/concepts
- type: x-dmca-policy
  url: https://cloud.google.com/storage/docs/dmca
- type: x-faq
  url: https://cloud.google.com/storage/docs/faq
- type: x-getting-started
  url: https://cloud.google.com/storage/docs/quickstarts
- type: x-guides
  url: https://cloud.google.com/storage/docs/how-to
- type: x-pricing
  url: https://cloud.google.com/storage/pricing
- type: x-service-level-agreements
  url: https://cloud.google.com/storage/sla
- type: x-support
  url: https://cloud.google.com/storage/docs/resources-support
- type: x-tutorials
  url: https://cloud.google.com/storage/docs/tutorials
- type: x-website
  url: https://cloud.google.com/storage/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---