---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Water Act
    (CWA) Rest Services Clean Water Act (CWA) Metadata Service
  description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
    parameter for get_qid, get_facility_info and other service endpoints.
  contact:
    name: US EPA, OECA Integration, Targeting and Access Branch
  version: 0.0.0
host: ofmpub.epa.gov
basePath: /echo
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /cwa_rest_services.metadata:
    get:
      summary: Clean Water Act (CWA) Metadata Service
      description: Returns the JSON Object Name and ColumnId for usage with the qcolumns
        parameter for get_qid, get_facility_info and other service endpoints.
      operationId: returns-the-json-object-name-and-columnid-for-usage-with-the-qcolumns-parameter-for-get-qid-get-faci
      x-api-path-slug: cwa-rest-services-metadata-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Clean
      - Water
      - Act
      - (CWA)
      - Metadata
      - Service
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