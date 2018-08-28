---
swagger: "2.0"
x-collection-name: Cisco WebEx
x-complete: 0
info:
  title: WebEx Teams API List rooms
  description: "List rooms.\r\n\r\nBy default, lists rooms to which the authenticated
    user belongs.\r\n\r\nhttps://developer.webex.com/endpoint-rooms-get.html"
  version: 1.0.0
host: api.ciscospark.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rooms:
    get:
      summary: List rooms
      description: "List rooms.\r\n\r\nBy default, lists rooms to which the authenticated
        user belongs.\r\n\r\nhttps://developer.webex.com/endpoint-rooms-get.html"
      operationId: RoomsGet3
      x-api-path-slug: rooms-get
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - List
      - Rooms
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