{
  "info": {
    "name": "Mota Word Get a list of realtime activities.",
    "_postman_id": "04632c32-3bf5-4fe5-b711-966d822fbb08",
    "description": "Get a list of realtime activities on the project, such as translation suggestion and translation approval.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Projects",
      "item": [
        {
          "id": "075143ca-dab3-48ff-819c-b473f90e48f8",
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
              "id": "50a64666-de61-4adb-8491-826a20f0efc1"
            }
          ]
        }
      ]
    }
  ]
}