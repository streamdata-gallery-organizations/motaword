---
name: MotaWord
x-slug: motaword
description: MotaWord is the world&rsquo;s fastest, lowest cost, cloud-based, collaborative
  business translation platform.MotaWord combines the efforts of talented human translators
  through the use of a cloud based translation platform. Our translators are able
  to login simultaneously into projects that fit their language combination and provide
  translation service collaboratively - while also seeing the whole content for contextual
  purposes. This ability to simultaneously utilize multiple translators makes MotaWord
  exceptionally fast and highly accurate.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: MotaWord
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/apis.md
specificationVersion: "0.14"
apis:
- name: Mota Word Available endpoints
  x-api-slug: mota-word
  description: The root endpoint will provide you a JSON Swagger definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////
  tags: ""
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/get-openapi.md
- name: Mota Word Get a list of supported formats
  x-api-slug: mota-word
  description: Get a list of supported formats for documents, style guides and extensions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////formats
  tags: Formats
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/formats-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/formats-get-openapi.md
- name: Mota Word Download the global glossary.
  x-api-slug: mota-word
  description: Download your corporate account's global glossary. This endpoint is
    available only for corporate account customers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////glossary
  tags: Glossary
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/glossary-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/glossary-get-openapi.md
- name: Mota Word Create or update the global glossary.
  x-api-slug: mota-word
  description: Update your corporate account's global glossary. This endpoint is available
    only for corporate account customers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////glossary
  tags: Glossary
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/glossary-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/glossary-post-openapi.md
- name: Mota Word Get a list of supported languages
  x-api-slug: mota-word
  description: Get a list of supported languages.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////languages
  tags: Languages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/languages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/languages-get-openapi.md
- name: Mota Word Get your account information and summary.
  x-api-slug: mota-word
  description: Get your account information and summary..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////me
  tags: Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/me-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/me-get-openapi.md
- name: Mota Word Get a list of your projects
  x-api-slug: mota-word
  description: Get a list of your projects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects
  tags: Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projects-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projects-get-openapi.md
- name: Mota Word Get a new quote
  x-api-slug: mota-word
  description: Create a new project
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects
  tags: Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projects-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projects-post-openapi.md
- name: Mota Word Delete a project
  x-api-slug: mota-word
  description: Delete(cancel) a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{id}
  tags: Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsid-delete-openapi.md
- name: Mota Word Get single project
  x-api-slug: mota-word
  description: Get single project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{id}
  tags: Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsid-get-openapi.md
- name: Mota Word Update project language pairs
  x-api-slug: mota-word
  description: Update project language pairs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{id}
  tags: Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsid-put-openapi.md
- name: Mota Word Trigger a call to your callback URL related to this project.
  x-api-slug: mota-word
  description: Trigger a call to your callback url related to this project..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{id}/callback/{actionType}
  tags: Projects,Callback,ActionType
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidcallbackactiontype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidcallbackactiontype-get-openapi.md
- name: Mota Word Cancel your translation project
  x-api-slug: mota-word
  description: Cancel your translation project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{id}/cancel
  tags: Projects,Cancel
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidcancel-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidcancel-post-openapi.md
- name: Mota Word Download the latest translation package.
  x-api-slug: mota-word
  description: Download the latest translation package. You must have given a /package
    call beforehand and wait until the packaging status is 'completed'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{id}/download
  tags: Projects,Download
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsiddownload-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsiddownload-post-openapi.md
- name: Mota Word Download the latest translation package.
  x-api-slug: mota-word
  description: Download only the translation package of this language. You must have
    given a /package call beforehand and wait until the packaging status is 'completed'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{id}/download/{language}
  tags: Projects,Download,Language
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsiddownloadlanguage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsiddownloadlanguage-post-openapi.md
- name: Mota Word Launch your translation project
  x-api-slug: mota-word
  description: Launch your translation project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{id}/launch
  tags: Projects,Launch
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidlaunch-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidlaunch-post-openapi.md
- name: Mota Word Package the translation of all languages to be downloaded.
  x-api-slug: mota-word
  description: Package the translation project, make it ready to be downloaded.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{id}/package
  tags: Projects,Package
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidpackage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidpackage-post-openapi.md
- name: Mota Word Track the status of translation packaging.
  x-api-slug: mota-word
  description: This request will tell you the current progress of the translation
    packaging. You will use the 'key' provided by the /package call.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{id}/package/check
  tags: Projects,Package,Check
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidpackagecheck-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidpackagecheck-get-openapi.md
- name: Mota Word Package the translation of a specific target language to be downloaded.
  x-api-slug: mota-word
  description: Package the translation of a specific target language to be downloaded..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{id}/package/{language}
  tags: Projects,Package,Language
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidpackagelanguage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidpackagelanguage-post-openapi.md
- name: Mota Word Get project progress
  x-api-slug: mota-word
  description: Get the progress of an already launched project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{id}/progress
  tags: Projects,Progress
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidprogress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidprogress-get-openapi.md
- name: Mota Word Submit reports for a project
  x-api-slug: mota-word
  description: Submit reports for a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{id}/reports
  tags: Projects,Reports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidreports-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsidreports-post-openapi.md
- name: Mota Word Get a list of realtime activities.
  x-api-slug: mota-word
  description: Get a list of realtime activities on the project, such as translation
    suggestion and translation approval.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/activities
  tags: Projects,ProjectId,Activities
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidactivities-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidactivities-get-openapi.md
- name: Mota Word Get a single realtime activity.
  x-api-slug: mota-word
  description: Get a single realtime activity..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/activities/{activityId}
  tags: Projects,ProjectId,Activities,ActivityId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidactivitiesactivityid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidactivitiesactivityid-get-openapi.md
- name: Mota Word Submit a comment to an activity.
  x-api-slug: mota-word
  description: Submit a comment to an activity..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/activities/{activityId}
  tags: Projects,ProjectId,Activities,ActivityId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidactivitiesactivityid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidactivitiesactivityid-post-openapi.md
- name: Mota Word Get a list of comments belonging to this activity.
  x-api-slug: mota-word
  description: Get a list of comments belonging to this activity..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/activities/{activityId}/comments
  tags: Projects,ProjectId,Activities,ActivityId,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidactivitiesactivityidcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidactivitiesactivityidcomments-get-openapi.md
- name: Mota Word Get a list of activity comments throughout the whole project.
  x-api-slug: mota-word
  description: Get a list of activity comments throughout the whole project..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/comments
  tags: Projects,ProjectId,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidcomments-get-openapi.md
- name: Mota Word Get a list of documents
  x-api-slug: mota-word
  description: Get a list of documents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/documents
  tags: Projects,ProjectId,Documents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectiddocuments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectiddocuments-get-openapi.md
- name: Mota Word Upload a new document
  x-api-slug: mota-word
  description: Upload a new document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/documents
  tags: Projects,ProjectId,Documents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectiddocuments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectiddocuments-post-openapi.md
- name: Mota Word Delete the document
  x-api-slug: mota-word
  description: Delete the document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/documents/{documentId}
  tags: Projects,ProjectId,Documents,DocumentId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectiddocumentsdocumentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectiddocumentsdocumentid-delete-openapi.md
- name: Mota Word Get single document
  x-api-slug: mota-word
  description: Get single document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/documents/{documentId}
  tags: Projects,ProjectId,Documents,DocumentId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectiddocumentsdocumentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectiddocumentsdocumentid-get-openapi.md
- name: Mota Word Update the document.
  x-api-slug: mota-word
  description: Update the document. File name and contents will replaced with the
    new one.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/documents/{documentId}
  tags: Projects,ProjectId,Documents,DocumentId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectiddocumentsdocumentid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectiddocumentsdocumentid-put-openapi.md
- name: Mota Word Download a document
  x-api-slug: mota-word
  description: Download a document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/documents/{documentId}/download
  tags: Projects,ProjectId,Documents,DocumentId,Download
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectiddocumentsdocumentiddownload-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectiddocumentsdocumentiddownload-get-openapi.md
- name: Mota Word Get a list of glossaries
  x-api-slug: mota-word
  description: Get a list of glossaries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/glossaries
  tags: Projects,ProjectId,Glossaries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidglossaries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidglossaries-get-openapi.md
- name: Mota Word Upload a new glossary
  x-api-slug: mota-word
  description: Upload a new glossary.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/glossaries
  tags: Projects,ProjectId,Glossaries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidglossaries-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidglossaries-post-openapi.md
- name: Mota Word Delete the glossary
  x-api-slug: mota-word
  description: Delete the glossary.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/glossaries/{glossaryId}
  tags: Projects,ProjectId,Glossaries,GlossaryId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidglossariesglossaryid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidglossariesglossaryid-delete-openapi.md
- name: Mota Word Get single glossary
  x-api-slug: mota-word
  description: Get single glossary.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/glossaries/{glossaryId}
  tags: Projects,ProjectId,Glossaries,GlossaryId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidglossariesglossaryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidglossariesglossaryid-get-openapi.md
- name: Mota Word Update the glossary.
  x-api-slug: mota-word
  description: Update the glossary. File name and contents will replaced with the
    new one.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/glossaries/{glossaryId}
  tags: Projects,ProjectId,Glossaries,GlossaryId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidglossariesglossaryid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidglossariesglossaryid-put-openapi.md
- name: Mota Word Download a glossary
  x-api-slug: mota-word
  description: Download a glossary.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/glossaries/{glossaryId}/download
  tags: Projects,ProjectId,Glossaries,GlossaryId,Download
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidglossariesglossaryiddownload-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidglossariesglossaryiddownload-get-openapi.md
- name: Mota Word Get a list of style guides
  x-api-slug: mota-word
  description: Get a list of style guides.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/styleguides
  tags: Projects,ProjectId,Styleguides
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidstyleguides-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidstyleguides-get-openapi.md
- name: Mota Word Upload a new style guide
  x-api-slug: mota-word
  description: Upload a new style guide.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/styleguides
  tags: Projects,ProjectId,Styleguides
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidstyleguides-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidstyleguides-post-openapi.md
- name: Mota Word Delete the style guide
  x-api-slug: mota-word
  description: Delete the style guide.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/styleguides/{styleGuideId}
  tags: Projects,ProjectId,Styleguides,StyleGuideId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidstyleguidesstyleguideid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidstyleguidesstyleguideid-delete-openapi.md
- name: Mota Word Get single style guide
  x-api-slug: mota-word
  description: Get single style guide.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/styleguides/{styleGuideId}
  tags: Projects,ProjectId,Styleguides,StyleGuideId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidstyleguidesstyleguideid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidstyleguidesstyleguideid-get-openapi.md
- name: Mota Word Update the style guide.
  x-api-slug: mota-word
  description: Update the style guide. File name and contents will replaced with the
    new one.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/styleguides/{styleGuideId}
  tags: Projects,ProjectId,Styleguides,StyleGuideId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidstyleguidesstyleguideid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidstyleguidesstyleguideid-put-openapi.md
- name: Mota Word Download a style guide
  x-api-slug: mota-word
  description: Download a style guide.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/styleguides/{styleGuideId}/download
  tags: Projects,ProjectId,Styleguides,StyleGuideId,Download
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidstyleguidesstyleguideiddownload-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/projectsprojectidstyleguidesstyleguideiddownload-get-openapi.md
- name: Mota Word Download the global style guide.
  x-api-slug: mota-word
  description: Download your corporate account's global style guide. This endpoint
    is available only for corporate account customers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////styleguide
  tags: Styleguide
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/styleguide-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/styleguide-get-openapi.md
- name: Mota Word Create or update the global style guide.
  x-api-slug: mota-word
  description: Update your corporate account's global style guide. This endpoint is
    available only for corporate account customers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////styleguide
  tags: Styleguide
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/styleguide-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/styleguide-post-openapi.md
- name: Mota Word Retrieve an access token to interact with the API.
  x-api-slug: mota-word
  description: MotaWord API is using OAuth2 procedures when authenticating or authorizing
    your API call. Currently, we only allow Client Credential type flow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////token
  tags: Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/token-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/token-post-openapi.md
- name: Mota Word
  x-api-slug: mota-word
  description: MotaWord is the world&rsquo;s fastest, lowest cost, cloud-based, collaborative
    business translation platform.MotaWord combines the efforts of talented human
    translators through the use of a cloud based translation platform. Our translators
    are able to login simultaneously into projects that fit their language combination
    and provide translation service collaboratively - while also seeing the whole
    content for contextual purposes. This ability to simultaneously utilize multiple
    translators makes MotaWord exceptionally fast and highly accurate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com//
  tags: MotaWord
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/motaword/master/_listings/motaword/openapi.md
x-common:
- type: x-website
  url: http://www.motaword.com
- type: x-blog
  url: https://www.motaword.com/developer/blog
- type: x-developer
  url: https://www.motaword.com/developer
- type: x-github
  url: https://github.com/motaword
- type: x-pricing
  url: https://www.motaword.com/pricing
- type: x-twitter
  url: https://twitter.com/motaword
- type: x-website
  url: http://motaword.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---