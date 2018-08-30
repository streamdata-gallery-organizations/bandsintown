---
swagger: "2.0"
x-collection-name: Bandsintown
x-complete: 0
info:
  title: Bands in Town Get artist information
  description: Get artist information
  contact:
    name: Bandsintown
    url: https://bandsintown.com/
  version: 1.0.0
host: rest.bandsintown.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /artists/{artistname}:
    get:
      summary: Get artist information
      description: Get artist information
      operationId: artist
      x-api-path-slug: artistsartistname-get
      parameters:
      - in: query
        name: app_id
        description: The application ID assigned to you by Bandsintown
      - in: path
        name: artistname
        description: The name of the artist
      responses:
        200:
          description: OK
      tags:
      - Bands
      - Music
      - Concerts
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