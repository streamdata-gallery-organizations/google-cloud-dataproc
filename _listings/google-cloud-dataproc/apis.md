---
name: Google Cloud Dataproc
x-slug: google-cloud-dataproc
description: Use Google Cloud Dataproc, an Apache Hadoop, Apache Spark, Apache Pig,
  and Apache Hive service, to easily process big datasets at low cost. Control your
  costs by quickly creating managed clusters of any size and turning them off when
  youre done. Cloud Dataproc integrates across Google Cloud Platform products, giving
  you a powerful and complete data processing platform.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Cloud Dataproc
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Dataproc API Get Region Clusters
  x-api-slug: google-cloud-dataproc-api
  description: Lists all regions/{region}/clusters in a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/projects/{projectId}/regions/{region}/clusters
  tags: Cluster
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1projectsprojectidregionsregionclusters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1projectsprojectidregionsregionclusters-get-openapi.md
- name: Google Cloud Dataproc API Create Cluster
  x-api-slug: google-cloud-dataproc-api
  description: Creates a cluster in a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/projects/{projectId}/regions/{region}/clusters
  tags: Cluster
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1projectsprojectidregionsregionclusters-post-openapi.md
- name: Google Cloud Dataproc API Delete Cluster
  x-api-slug: google-cloud-dataproc-api
  description: Deletes a cluster in a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/projects/{projectId}/regions/{region}/clusters/{clusterName}
  tags: Cluster
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1projectsprojectidregionsregionclustersclustername-delete-openapi.md
- name: Google Cloud Dataproc API Get Cluster
  x-api-slug: google-cloud-dataproc-api
  description: Gets the resource representation for a cluster in a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/projects/{projectId}/regions/{region}/clusters/{clusterName}
  tags: Cluster
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1projectsprojectidregionsregionclustersclustername-get-openapi.md
- name: Google Cloud Dataproc API Update Cluster
  x-api-slug: google-cloud-dataproc-api
  description: Updates a cluster in a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/projects/{projectId}/regions/{region}/clusters/{clusterName}
  tags: Cluster
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1projectsprojectidregionsregionclustersclustername-patch-openapi.md
- name: Google Cloud Dataproc API Get Cluster Diagnostic
  x-api-slug: google-cloud-dataproc-api
  description: Gets cluster diagnostic information. After the operation completes,
    the Operation.response field contains DiagnoseClusterOutputLocation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/projects/{projectId}/regions/{region}/clusters/{clusterName}:diagnose
  tags: Cluster
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1projectsprojectidregionsregionclustersclusternamediagnose-post-openapi.md
- name: Google Cloud Dataproc API Get Region Jobs
  x-api-slug: google-cloud-dataproc-api
  description: Lists regions/{region}/jobs in a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/projects/{projectId}/regions/{region}/jobs
  tags: Job
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1projectsprojectidregionsregionjobs-get-openapi.md
- name: Google Cloud Dataproc API Delete Job
  x-api-slug: google-cloud-dataproc-api
  description: Deletes the job from the project. If the job is active, the delete
    fails, and the response returns FAILED_PRECONDITION.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/projects/{projectId}/regions/{region}/jobs/{jobId}
  tags: Job
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1projectsprojectidregionsregionjobsjobid-delete-openapi.md
- name: Google Cloud Dataproc API Get Job
  x-api-slug: google-cloud-dataproc-api
  description: Gets the resource representation for a job in a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/projects/{projectId}/regions/{region}/jobs/{jobId}
  tags: Job
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1projectsprojectidregionsregionjobsjobid-get-openapi.md
- name: Google Cloud Dataproc API Update Job
  x-api-slug: google-cloud-dataproc-api
  description: Updates a job in a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/projects/{projectId}/regions/{region}/jobs/{jobId}
  tags: Job
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1projectsprojectidregionsregionjobsjobid-patch-openapi.md
- name: Google Cloud Dataproc API Cancel Job
  x-api-slug: google-cloud-dataproc-api
  description: Starts a job cancellation request. To access the job resource after
    cancellation, call regions/{region}/jobs.list or regions/{region}/jobs.get.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/projects/{projectId}/regions/{region}/jobs/{jobId}:cancel
  tags: Job
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1projectsprojectidregionsregionjobsjobidcancel-post-openapi.md
- name: Google Cloud Dataproc API Submit Job
  x-api-slug: google-cloud-dataproc-api
  description: Submits a job to a cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/projects/{projectId}/regions/{region}/jobs:submit
  tags: Job
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1projectsprojectidregionsregionjobssubmit-post-openapi.md
- name: Google Cloud Dataproc API Delete Operation
  x-api-slug: google-cloud-dataproc-api
  description: Deletes a long-running operation. This method indicates that the client
    is no longer interested in the operation result. It does not cancel the operation.
    If the server doesn't support this method, it returns google.rpc.Code.UNIMPLEMENTED.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/{name}
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1name-delete-openapi.md
- name: Google Cloud Dataproc API Get Operation State
  x-api-slug: google-cloud-dataproc-api
  description: Gets the latest state of a long-running operation. Clients can use
    this method to poll the operation result at intervals as recommended by the API
    service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/{name}
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1name-get-openapi.md
- name: Google Cloud Dataproc API Start Cancellation
  x-api-slug: google-cloud-dataproc-api
  description: Starts asynchronous cancellation on a long-running operation. The server
    makes a best effort to cancel the operation, but success is not guaranteed. If
    the server doesn't support this method, it returns google.rpc.Code.UNIMPLEMENTED.
    Clients can use Operations.GetOperation or other methods to check whether the
    cancellation succeeded or whether the operation completed despite cancellation.
    On successful cancellation, the operation is not deleted; instead, it becomes
    an operation with an Operation.error value with a google.rpc.Status.code of 1,
    corresponding to Code.CANCELLED.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com////v1/{name}:cancel
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/v1namecancel-post-openapi.md
- name: Google Cloud Dataproc API
  x-api-slug: google-cloud-dataproc-api
  description: Use Google Cloud Dataproc, an Apache Hadoop, Apache Spark, Apache Pig,
    and Apache Hive service, to easily process big datasets at low cost. Control your
    costs by quickly creating managed clusters of any size and turning them off when
    youre done. Cloud Dataproc integrates across Google Cloud Platform products, giving
    you a powerful and complete data processing platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/dataproc.png
  humanURL: https://cloud.google.com/dataproc/
  baseURL: ://dataproc.googleapis.com//
  tags: Google Cloud Dataproc
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dataproc/master/_listings/google-cloud-dataproc/openapi.md
x-common:
- type: x-change-logs
  url: https://cloud.google.com/dataproc/docs/release-notes/service
- type: x-documentation
  url: https://cloud.google.com/dataproc/docs/
- type: x-faq
  url: https://cloud.google.com/dataproc/docs/resources/faq
- type: x-getting-started
  url: https://cloud.google.com/dataproc/docs/quickstarts
- type: x-guides
  url: https://cloud.google.com/dataproc/docs/how-to
- type: x-partners
  url: https://cloud.google.com/dataproc/docs/resources/partners
- type: x-pricing
  url: https://cloud.google.com/dataproc/docs/resources/pricing
- type: x-rate-limits
  url: https://cloud.google.com/dataproc/quotas
- type: x-sdk
  url: https://cloud.google.com/dataproc/docs/gcloud-installation
- type: x-service-level-agreements
  url: https://cloud.google.com/dataproc/docs/resources/sla
- type: x-support
  url: https://cloud.google.com/dataproc/docs/support/get-support
- type: x-website
  url: https://cloud.google.com/dataproc/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---