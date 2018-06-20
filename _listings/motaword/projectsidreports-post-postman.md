{
  "info": {
    "name": "Mota Word Submit reports for a project",
    "_postman_id": "48aaeb6f-2045-408a-91d2-11646e9eba07",
    "description": "Submit reports for a project.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Projects",
      "item": [
        {
          "id": "897dacfd-9d16-439e-90b9-8a4305d05cd8",
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
              "id": "f8b5f6e3-7c42-413a-b108-b7886bdf9b0e"
            }
          ]
        },
        {
          "id": "9d75ec4a-bc15-44a8-b1a4-3ede2b32127f",
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
              "id": "7285dc09-acdb-43cf-9a81-b279a0b004c0"
            }
          ]
        },
        {
          "id": "daf95f5c-3b37-4783-8efe-64e9f1cd1c68",
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
              "id": "8236a92e-791b-4faf-ba1c-464940051249"
            }
          ]
        },
        {
          "id": "b1835975-98d9-42e1-a23e-98fa3a883a3b",
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
              "id": "2537f99e-3774-44d2-89fc-3a7c8ab34235"
            }
          ]
        },
        {
          "id": "72dca7cd-0af2-4480-acf7-3ef4d55a5c96",
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
              "id": "c9fedfbc-875d-4efb-9ddc-8bdaea94e959"
            }
          ]
        },
        {
          "id": "af0ed009-378e-42ef-b304-026401b260c3",
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
              "id": "7c90e525-806b-405b-ab36-0bf03c7ce2a3"
            }
          ]
        },
        {
          "id": "e71e2c47-b6a3-4490-b426-b4c388c20d28",
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
              "id": "9690acd5-5bf1-4234-af66-947b4fa3b4cd"
            }
          ]
        },
        {
          "id": "0e9e3015-8208-4ae0-9a7b-fc663b4d3de4",
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
              "id": "1cdcbae7-e60a-4789-a751-1ab128891fa8"
            }
          ]
        },
        {
          "id": "33dc578a-7195-42a5-b17d-0a10ece6109e",
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
              "id": "f966394f-e008-488e-ba6d-c8eaa0710c49"
            }
          ]
        },
        {
          "id": "b3af94df-09c9-4180-a22e-06bfe5ab81e0",
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
              "id": "93dab7e6-7313-4bb5-8cc3-4dd34c731779"
            }
          ]
        },
        {
          "id": "e96e2ea9-0e82-4d02-ab41-7e063ecdcf40",
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
              "id": "1be8b1d4-38dc-4c99-862c-6495ad8351b0"
            }
          ]
        },
        {
          "id": "d017c61c-4786-47b3-a8a7-f00ce631d99d",
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
              "id": "0b66cec4-3998-4853-a337-3b352e8e51bd"
            }
          ]
        },
        {
          "id": "433f9fe4-ea08-4a13-892a-fd6877661ae5",
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
              "id": "35114615-f59c-497a-b772-7d14d0913a8a"
            }
          ]
        },
        {
          "id": "9ced66fd-a52d-4b60-a427-d995b69ae4d3",
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
              "id": "5cd615af-6ecc-4d7c-bdef-28e64909ac38"
            }
          ]
        },
        {
          "id": "5c06c2c0-0eb6-4066-a21d-11f9925c64dd",
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
              "id": "8c6ff7fd-47e5-498e-8616-2fffcc293d47"
            }
          ]
        }
      ]
    }
  ]
}