---
swagger: "2.0"
info:
  title: SoundCloud Get My Following
  description: Checks if the user with the id contact_id is in the logged-in user's
    list of contacts.
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
  /me/followings/{contact_id}.json:
    get:
      summary: Get My Following
      description: Checks if the user with the id contact_id is in the logged-in user's
        list of contacts
      operationId: me.followings.contact_id.json.get
      responses:
        200:
          description: OK
      tags:
      - audio
      - me
      - favorites
      - tracks
definitions: []
x-collection-name: SoundCloud
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