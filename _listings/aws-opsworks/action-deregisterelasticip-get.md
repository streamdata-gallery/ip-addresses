---
swagger: "2.0"
info:
  title: AWS OpsWorks API Deregister Elastic IP
  version: 1.0.0
  description: Deregisters a specified Elastic IP address.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeregisterElasticIp:
    get:
      summary: ' Deregister Elastic IP'
      description: Deregisters a specified Elastic IP address
      operationId: deregisterElasticIp
      parameters:
      - in: query
        name: ElasticIp
        description: The Elastic IP address
        type: string
      responses:
        200:
          description: OK
      tags:
      - ip addresses
definitions: []
x-collection-name: AWS OpsWorks
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