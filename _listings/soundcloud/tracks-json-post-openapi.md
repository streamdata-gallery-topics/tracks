---
swagger: "2.0"
x-collection-name: SoundCloud
x-complete: 0
info:
  title: Sound Cloud Post Tracks
  description: Uploads a track
  version: 1.0.0
host: api.soundcloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tracks.json:
    get:
      summary: Get Tracks
      description: Returns a collection of tracks
      operationId: getTracks.json
      x-api-path-slug: tracks-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Tracks
    post:
      summary: Post Tracks
      description: Uploads a track
      operationId: postTracks.json
      x-api-path-slug: tracks-json-post
      responses:
        200:
          description: OK
      tags:
      - Tracks
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