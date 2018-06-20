---
swagger: "2.0"
x-collection-name: MotaWord
x-complete: 0
info:
  title: Mota Word Cancel your translation project
  description: Cancel your translation project.
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
  /projects:
    get:
      summary: Get a list of your projects
      description: Get a list of your projects.
      operationId: getProjects
      x-api-path-slug: projects-get
      parameters:
      - in: query
        name: page
      - in: query
        name: per_page
      responses:
        200:
          description: OK
      tags:
      - Projects
    post:
      summary: Get a new quote
      description: Create a new project
      operationId: createProject
      x-api-path-slug: projects-post
      parameters:
      - in: formData
        name: callback_url
        description: Optional
      - in: formData
        name: custom
        description: Optional
      - in: formData
        name: documents[]
        description: Optional
      - in: formData
        name: glossaries[]
        description: Optional
      - in: formData
        name: source_language
      - in: formData
        name: styleguides[]
        description: Optional
      - in: formData
        name: target_languages[]
      responses:
        200:
          description: OK
      tags:
      - Projects
  /projects/{id}:
    delete:
      summary: Delete a project
      description: Delete(cancel) a project.
      operationId: deleteProject
      x-api-path-slug: projectsid-delete
      parameters:
      - in: path
        name: id
        description: Project ID
      responses:
        200:
          description: OK
      tags:
      - Projects
    get:
      summary: Get single project
      description: Get single project.
      operationId: getProject
      x-api-path-slug: projectsid-get
      parameters:
      - in: path
        name: id
        description: Project ID
      responses:
        200:
          description: OK
      tags:
      - Projects
    put:
      summary: Update project language pairs
      description: Update project language pairs.
      operationId: updateProject
      x-api-path-slug: projectsid-put
      parameters:
      - in: formData
        name: callback_url
        description: Optional
      - in: formData
        name: custom
        description: Optional
      - in: path
        name: id
        description: Project ID
      - in: formData
        name: source_language
      - in: formData
        name: target_languages[]
      responses:
        200:
          description: OK
      tags:
      - Projects
  /projects/{id}/callback/{actionType}:
    get:
      summary: Trigger a call to your callback URL related to this project.
      description: Trigger a call to your callback url related to this project..
      operationId: triggerCallback
      x-api-path-slug: projectsidcallbackactiontype-get
      parameters:
      - in: path
        name: actionType
        description: Callback type
      - in: path
        name: id
        description: Project ID
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Callback
      - ActionType
  /projects/{id}/cancel:
    post:
      summary: Cancel your translation project
      description: Cancel your translation project.
      operationId: cancelProject
      x-api-path-slug: projectsidcancel-post
      parameters:
      - in: path
        name: id
        description: Project ID
      - in: formData
        name: reason
        description: Cancellation reason
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Cancel
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