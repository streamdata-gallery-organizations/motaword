{
  "info": {
    "name": "Mota Word Download the global style guide.",
    "_postman_id": "bdb168b6-58c5-48a5-8faa-f63493191032",
    "description": "Download your corporate account's global style guide. This endpoint is available only for corporate account customers.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Folder",
      "item": [
        {
          "id": "bd7656a3-2ae9-4874-89f0-5d4a0647a12f",
          "name": "getEndpoints",
          "request": {
            "url": "http://api.motaword.com/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The root endpoint will provide you a JSON Swagger definition."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09340b16-09a5-4b86-9bd7-e4c04e8faee8"
            }
          ]
        }
      ]
    },
    {
      "name": "Formats",
      "item": [
        {
          "id": "31f52666-b250-4c43-b150-d0b0786fcd3d",
          "name": "getFormats",
          "request": {
            "url": "http://api.motaword.com/formats",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of supported formats for documents, style guides and extensions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "464cca44-df1c-4ad7-b238-cb007d01c670"
            }
          ]
        }
      ]
    },
    {
      "name": "Glossary",
      "item": [
        {
          "id": "b11c0826-1c5f-4ee6-aaca-1a29b469aa9f",
          "name": "downloadGlobalGlossary",
          "request": {
            "url": "http://api.motaword.com/glossary",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Download your corporate account's global glossary. This endpoint is available only for corporate account customers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ccaf912-4afb-4d65-abff-ff559eee428c"
            }
          ]
        },
        {
          "id": "78eddcf2-4c10-4963-950b-0bfeef3133fb",
          "name": "updateGlobalGlossary",
          "request": {
            "url": "http://api.motaword.com/glossary",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "glossary",
                  "value": "{}",
                  "disabled": false,
                  "description": "Glossary file"
                }
              ]
            },
            "description": "Update your corporate account's global glossary. This endpoint is available only for corporate account customers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1bd327f7-13ca-4591-af18-671afa6a2043"
            }
          ]
        }
      ]
    },
    {
      "name": "Languages",
      "item": [
        {
          "id": "e94e32fc-9e55-43c0-bc7d-f4b2bd3f2086",
          "name": "getLanguages",
          "request": {
            "url": "http://api.motaword.com/languages",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of supported languages."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0c840b3-4553-4344-9d28-59795a7a3581"
            }
          ]
        }
      ]
    },
    {
      "name": "Me",
      "item": [
        {
          "id": "dd6b1db9-02b1-4af1-b670-1f46e68b7cc8",
          "name": "getAccount",
          "request": {
            "url": "http://api.motaword.com/me",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get your account information and summary.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6466620-0a78-4751-80a6-17f8ac255213"
            }
          ]
        }
      ]
    },
    {
      "name": "Projects",
      "item": [
        {
          "id": "72d9e36d-9c7b-4ff5-8ebc-afe992e1f09a",
          "name": "getProjects",
          "request": {
            "url": "http://api.motaword.com/projects?page=%7B%7D&per_page=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of your projects."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "acf63476-de48-4d05-9374-dc2a7a30481e"
            }
          ]
        },
        {
          "id": "97a71c63-99e9-43fd-a28b-3c1732be9c60",
          "name": "createProject",
          "request": {
            "url": "http://api.motaword.com/projects",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "callback_url",
                  "value": "{}",
                  "disabled": false,
                  "description": "Optional"
                },
                {
                  "key": "custom",
                  "value": "{}",
                  "disabled": false,
                  "description": "Optional"
                },
                {
                  "key": "documents",
                  "value": "[{}]",
                  "disabled": false,
                  "description": "Optional"
                },
                {
                  "key": "glossaries",
                  "value": "[{}]",
                  "disabled": false,
                  "description": "Optional"
                },
                {
                  "key": "source_language",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "styleguides",
                  "value": "[{}]",
                  "disabled": false,
                  "description": "Optional"
                },
                {
                  "key": "target_languages",
                  "value": "[{}]",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Create a new project"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a462dc28-2d57-4daa-8996-c8e0d31b1158"
            }
          ]
        },
        {
          "id": "ad7bc70b-0249-495e-b6eb-ffe38f80b996",
          "name": "getProject",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get single project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a4cb55cd-7496-4b1c-b257-119067dfbcab"
            }
          ]
        },
        {
          "id": "a7222492-a9d3-4818-80e9-82ef1232a617",
          "name": "updateProject",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "callback_url",
                  "value": "{}",
                  "disabled": false,
                  "description": "Optional"
                },
                {
                  "key": "custom",
                  "value": "{}",
                  "disabled": false,
                  "description": "Optional"
                },
                {
                  "key": "source_language",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "target_languages",
                  "value": "[{}]",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Update project language pairs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "25f6b0ce-f684-47ce-a4c6-86e3178066bf"
            }
          ]
        },
        {
          "id": "d3e803aa-7eab-469d-bc2e-be0463adfcad",
          "name": "deleteProject",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete(cancel) a project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b58c62d-f619-4e7b-8320-ca643fbaf34e"
            }
          ]
        },
        {
          "id": "03b3cfff-5630-4866-a84a-709240eb4a53",
          "name": "triggerCallback",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:id/callback/:actionType"
              ],
              "variable": [
                {
                  "id": "actionType",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Trigger a call to your callback url related to this project.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5105c972-f4f3-44d9-b1b6-ffe434e26389"
            }
          ]
        },
        {
          "id": "02ded75c-518b-44b5-bb02-8d469d15142f",
          "name": "cancelProject",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:id/cancel"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "reason",
                  "value": "{}",
                  "disabled": false,
                  "description": "Cancellation reason"
                }
              ]
            },
            "description": "Cancel your translation project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54718cd2-f9d3-4b21-b112-300119873d32"
            }
          ]
        },
        {
          "id": "56620035-77a1-49bc-b4d7-104da48409ad",
          "name": "download",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:id/download"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Download the latest translation package. You must have given a /package call beforehand and wait until the packaging status is 'completed'."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10501b33-791f-4329-8b54-bb2f8e28f2c6"
            }
          ]
        },
        {
          "id": "b40c6d95-c656-4c24-8cc4-d4943e5f2a4a",
          "name": "downloadLanguage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:id/download/:language"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "language",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Download only the translation package of this language. You must have given a /package call beforehand and wait until the packaging status is 'completed'."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27a1f548-9ad1-418c-b018-193ae0684eb0"
            }
          ]
        },
        {
          "id": "b95bcd2d-7014-4f95-aa62-99c60c8218d3",
          "name": "launchProject",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:id/launch"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "budget_code",
                  "value": "{}",
                  "disabled": false,
                  "description": "Optional with corporate accounts"
                },
                {
                  "key": "payment_code",
                  "value": "{}",
                  "disabled": false,
                  "description": "Optional"
                },
                {
                  "key": "payment_method",
                  "value": "{}",
                  "disabled": false,
                  "description": "Optional"
                }
              ]
            },
            "description": "Launch your translation project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "245c6b4c-54e0-40a6-b210-ee96913290ef"
            }
          ]
        },
        {
          "id": "88ff818c-2a89-4c75-b90a-7cfc259a8a68",
          "name": "package",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:id/package"
              ],
              "query": [
                {
                  "key": "async",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Package the translation project, make it ready to be downloaded."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "383156d3-0d3f-4b9b-b5e1-f6f842bca1d7"
            }
          ]
        },
        {
          "id": "34ef5cb7-1a8b-4a40-9353-f68be7b7cebc",
          "name": "trackPackage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:id/package/check"
              ],
              "query": [
                {
                  "key": "key",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This request will tell you the current progress of the translation packaging. You will use the 'key' provided by the /package call."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d7a2cec0-0bb2-4442-9630-2fc8882c5ccb"
            }
          ]
        },
        {
          "id": "18c99f41-7767-45a3-ab18-23ae74d3c19e",
          "name": "packageLanguage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:id/package/:language"
              ],
              "query": [
                {
                  "key": "async",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "language",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Package the translation of a specific target language to be downloaded.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "587112f8-b812-45ae-9b9b-9615dfe8c766"
            }
          ]
        },
        {
          "id": "fd371790-60a2-40bb-8599-441b527d8122",
          "name": "getProgress",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:id/progress"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the progress of an already launched project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92770cbe-df46-4d46-b9b0-2a3387e47fb5"
            }
          ]
        },
        {
          "id": "40c51cf2-e83c-4512-be7e-6bbbf4259561",
          "name": "submitProjectReports",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:id/reports"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "activity_type",
                  "value": "{}",
                  "disabled": false,
                  "description": "Activity Type"
                },
                {
                  "key": "message",
                  "value": "{}",
                  "disabled": false,
                  "description": "Report Message"
                }
              ]
            },
            "description": "Submit reports for a project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7da8c96a-4161-4cb8-aa7c-f55192b5fcc1"
            }
          ]
        },
        {
          "id": "94592098-3ca1-4e5f-b6f4-79cb799068cb",
          "name": "getActivities",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/activities"
              ],
              "query": [
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "per_page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of realtime activities on the project, such as translation suggestion and translation approval."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d799f986-c862-491f-a74f-ce35bb55c0e7"
            }
          ]
        },
        {
          "id": "82a89113-66b1-4d7e-a10c-74021e681440",
          "name": "getActivity",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/activities/:activityId"
              ],
              "variable": [
                {
                  "id": "activityId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a single realtime activity.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "72992cb0-22e1-4622-aa36-426d02e08ded"
            }
          ]
        },
        {
          "id": "d8c165dc-a807-42a9-af01-5eb5a3ea1d46",
          "name": "submitComment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/activities/:activityId"
              ],
              "variable": [
                {
                  "id": "activityId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "comment",
                  "value": "{}",
                  "disabled": false,
                  "description": "Comment text"
                }
              ]
            },
            "description": "Submit a comment to an activity.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "083f62b3-6e70-470c-a271-5f8a929f0abb"
            }
          ]
        },
        {
          "id": "530229fc-9b16-447f-9a99-5effaf98f9cb",
          "name": "getActivityComments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/activities/:activityId/comments"
              ],
              "variable": [
                {
                  "id": "activityId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of comments belonging to this activity.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be8b5a26-73ff-4d5f-a454-8c44ffbc50b7"
            }
          ]
        },
        {
          "id": "e8599f93-de64-49fe-a39d-4a745141fc1a",
          "name": "getComments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/comments"
              ],
              "query": [
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "per_page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of activity comments throughout the whole project.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a82b636-86d2-4a28-a26e-f602a7db70ef"
            }
          ]
        },
        {
          "id": "3430b0e2-8fb4-45f5-9490-0ee984f67ec4",
          "name": "getDocuments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/documents"
              ],
              "variable": [
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of documents."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51db14cc-3fbb-46c4-aa47-2cbfc4eccbef"
            }
          ]
        },
        {
          "id": "285a6029-c429-4366-ae64-e28d004b2d5b",
          "name": "createDocument",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/documents"
              ],
              "variable": [
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "documents",
                  "value": "[{}]",
                  "disabled": false,
                  "description": "You can add as many files as you want in documents[] parameter"
                },
                {
                  "key": "schemes",
                  "value": "[{}]",
                  "disabled": false,
                  "description": "JSON string"
                }
              ]
            },
            "description": "Upload a new document."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "acd045ef-8bbd-424b-8583-5403279c5ef9"
            }
          ]
        },
        {
          "id": "834cbaae-96cd-425a-8e44-6a552d9746b7",
          "name": "getDocument",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/documents/:documentId"
              ],
              "variable": [
                {
                  "id": "documentId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get single document."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50fa3146-e7aa-4196-87ac-3b1b43e84364"
            }
          ]
        },
        {
          "id": "8bd6e94e-6b05-4622-b33c-2c960ced1567",
          "name": "updateDocument",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/documents/:documentId"
              ],
              "variable": [
                {
                  "id": "documentId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "documents",
                  "value": "{}",
                  "disabled": false,
                  "description": "Single file data"
                },
                {
                  "key": "schemes",
                  "value": "{}",
                  "disabled": false,
                  "description": "JSON string"
                }
              ]
            },
            "description": "Update the document. File name and contents will replaced with the new one."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d55c97cc-6aa5-4da3-9eed-94693c5933da"
            }
          ]
        },
        {
          "id": "dbcd488e-26b2-4d44-a07c-e86717ece4df",
          "name": "deleteDocument",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/documents/:documentId"
              ],
              "variable": [
                {
                  "id": "documentId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete the document."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "897a1593-8344-488d-b605-0e85a368d9ee"
            }
          ]
        },
        {
          "id": "a215c852-1fc7-44f9-b171-b02750669ceb",
          "name": "downloadDocument",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/documents/:documentId/download"
              ],
              "variable": [
                {
                  "id": "documentId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Download a document."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6635780a-23fa-4046-ad75-a20049530d75"
            }
          ]
        },
        {
          "id": "9052ef8b-364a-42cb-af83-017a8526b311",
          "name": "getGlossaries",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/glossaries"
              ],
              "variable": [
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of glossaries."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e61a1752-a5df-423e-9d01-d195e7e1b9b1"
            }
          ]
        },
        {
          "id": "5a95b520-e464-4c9d-bde9-245f2cf01171",
          "name": "createGlossary",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/glossaries"
              ],
              "variable": [
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "glossaries",
                  "value": "{}",
                  "disabled": false,
                  "description": "You can only add one glossary, even though the name suggests multiple glossaries"
                }
              ]
            },
            "description": "Upload a new glossary."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95e78636-11f8-48f8-bc44-c3dbd2ed8c2b"
            }
          ]
        },
        {
          "id": "9f50a671-1b77-4f7b-af14-ae2c65ce26b2",
          "name": "getGlossary",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/glossaries/:glossaryId"
              ],
              "variable": [
                {
                  "id": "glossaryId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get single glossary."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7f77cd3-47c8-4b1f-99c8-8d1fb4d911b3"
            }
          ]
        },
        {
          "id": "e79efa52-eee7-4bbb-ba49-af574ceb85fb",
          "name": "updateGlossary",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/glossaries/:glossaryId"
              ],
              "variable": [
                {
                  "id": "glossaryId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "glossaries",
                  "value": "{}",
                  "disabled": false,
                  "description": "Single file data"
                }
              ]
            },
            "description": "Update the glossary. File name and contents will replaced with the new one."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50cdfba6-ee59-4628-aaa6-5fdd321a9bc4"
            }
          ]
        },
        {
          "id": "dc76e258-8934-4341-9d2a-b3f041ac4710",
          "name": "deleteGlossary",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/glossaries/:glossaryId"
              ],
              "variable": [
                {
                  "id": "glossaryId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete the glossary."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3615dfab-3a22-49fb-b0df-34e28434ecf8"
            }
          ]
        },
        {
          "id": "9841293b-217a-46d6-afdb-65b8434017a2",
          "name": "downloadGlossary",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/glossaries/:glossaryId/download"
              ],
              "variable": [
                {
                  "id": "glossaryId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Download a glossary."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54ea2764-62c6-437f-893d-f387842f623a"
            }
          ]
        },
        {
          "id": "6d199ea1-7d1f-4879-a2ec-94d5bf29d2b8",
          "name": "getStyleGuides",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/styleguides"
              ],
              "variable": [
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of style guides."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7867670e-a3a6-4265-bf6f-588643509611"
            }
          ]
        },
        {
          "id": "2b8a697f-7567-40c2-bbf6-d1f3b3c48d9f",
          "name": "createStyleGuide",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/styleguides"
              ],
              "variable": [
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "styleguides",
                  "value": "[{}]",
                  "disabled": false,
                  "description": "You can add as many files as you want in styleguides[] parameter"
                }
              ]
            },
            "description": "Upload a new style guide."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d4f817cd-efab-43af-8dad-14e292f375fe"
            }
          ]
        },
        {
          "id": "eb7d152a-9c1f-4303-bceb-1f39a74044e0",
          "name": "getStyleGuide",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/styleguides/:styleGuideId"
              ],
              "variable": [
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "styleGuideId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get single style guide."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a7a484b2-caba-4422-9e60-6c9ba1352228"
            }
          ]
        },
        {
          "id": "b8ac09c5-74f4-4cc8-b623-1ab8f1092cd3",
          "name": "updateStyleGuide",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/styleguides/:styleGuideId"
              ],
              "variable": [
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "styleGuideId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "styleguides",
                  "value": "{}",
                  "disabled": false,
                  "description": "Single file data"
                }
              ]
            },
            "description": "Update the style guide. File name and contents will replaced with the new one."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0dfbd74d-38a2-48cb-812a-8801f609da1b"
            }
          ]
        },
        {
          "id": "2ecc66d1-c885-424a-b725-0c70b0abb03b",
          "name": "deleteStyleGuide",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/styleguides/:styleGuideId"
              ],
              "variable": [
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "styleGuideId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete the style guide."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05036588-9ac6-49a9-9b24-1bbda78aa35e"
            }
          ]
        },
        {
          "id": "2e582f97-6fd8-49c3-be06-d0594884b5ad",
          "name": "downloadStyleGuide",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.motaword.com",
              "path": [
                "projects/:projectId/styleguides/:styleGuideId/download"
              ],
              "variable": [
                {
                  "id": "projectId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "styleGuideId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Download a style guide."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ddb71720-40f6-4900-a139-297a0c43e92e"
            }
          ]
        }
      ]
    },
    {
      "name": "Styleguide",
      "item": [
        {
          "id": "30758477-8866-46af-9ca5-c116f514816e",
          "name": "downloadGlobalStyleGuide",
          "request": {
            "url": "http://api.motaword.com/styleguide",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Download your corporate account's global style guide. This endpoint is available only for corporate account customers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b4409ac5-b6af-4e88-bc2a-3e6dfcbace57"
            }
          ]
        }
      ]
    }
  ]
}