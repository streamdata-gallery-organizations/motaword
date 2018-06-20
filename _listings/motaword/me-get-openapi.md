---
swagger: "2.0"
x-collection-name: MotaWord
x-complete: 0
info:
  title: Mota Word Get your account information and summary.
  description: Get your account information and summary..
  version: alpha-0.1.0
host: api.motaword.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:
    get:
      summary: Available endpoints
      description: The root endpoint will provide you a JSON Swagger definition.
      operationId: getEndpoints
      x-api-path-slug: get
      responses:
        200:
          description: OK
      tags:
      - ""
  /formats:
    get:
      summary: Get a list of supported formats
      description: Get a list of supported formats for documents, style guides and
        extensions.
      operationId: getFormats
      x-api-path-slug: formats-get
      responses:
        200:
          description: OK
      tags:
      - Formats
  /glossary:
    get:
      summary: Download the global glossary.
      description: Download your corporate account's global glossary. This endpoint
        is available only for corporate account customers.
      operationId: downloadGlobalGlossary
      x-api-path-slug: glossary-get
      responses:
        200:
          description: OK
      tags:
      - Glossary
    post:
      summary: Create or update the global glossary.
      description: Update your corporate account's global glossary. This endpoint
        is available only for corporate account customers.
      operationId: updateGlobalGlossary
      x-api-path-slug: glossary-post
      parameters:
      - in: formData
        name: glossary
        description: Glossary file
      responses:
        200:
          description: OK
      tags:
      - Glossary
  /languages:
    get:
      summary: Get a list of supported languages
      description: Get a list of supported languages.
      operationId: getLanguages
      x-api-path-slug: languages-get
      responses:
        200:
          description: OK
      tags:
      - Languages
  /me:
    get:
      summary: Get your account information and summary.
      description: Get your account information and summary..
      operationId: getAccount
      x-api-path-slug: me-get
      responses:
        200:
          description: OK
      tags:
      - Me
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