---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Logout
  description: Logs out the back end user from plentymarkets. The access token expires.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/account/logout:
    post:
      summary: Logout
      description: Logs out the front end user from the online store. The access token
        expires.
      operationId: postRestAccountLogout
      x-api-path-slug: restaccountlogout-post
      responses:
        200:
          description: OK
      tags:
      - Logout
  /rest/logout:
    post:
      summary: Logout
      description: Logs out the back end user from plentymarkets. The access token
        expires.
      operationId: postRestLogout
      x-api-path-slug: restlogout-post
      responses:
        200:
          description: OK
      tags:
      - Logout
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