---
swagger: "2.0"
x-collection-name: Google Cloud Dataproc
x-complete: 0
info:
  title: Google Cloud Dataproc API Get Region Clusters
  description: Lists all regions/{region}/clusters in a project.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: dataproc.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/projects/{projectId}/regions/{region}/clusters:
    get:
      summary: Get Region Clusters
      description: Lists all regions/{region}/clusters in a project.
      operationId: dataproc.projects.regions.clusters.list
      x-api-path-slug: v1projectsprojectidregionsregionclusters-get
      parameters:
      - in: query
        name: filter
        description: Optional A filter constraining the clusters to list
      - in: query
        name: pageSize
        description: Optional The standard List page size
      - in: query
        name: pageToken
        description: Optional The standard List page token
      - in: path
        name: projectId
        description: Required The ID of the Google Cloud Platform project that the
          cluster belongs to
      - in: path
        name: region
        description: Required The Cloud Dataproc region in which to handle the request
      responses:
        200:
          description: OK
      tags:
      - Cluster
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