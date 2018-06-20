{
  "info": {
    "name": "Mota Word Submit a comment to an activity.",
    "_postman_id": "a443629c-4a09-4dc6-899c-9f334cf8b2cf",
    "description": "Submit a comment to an activity..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Projects",
      "item": [
        {
          "id": "38a522d6-3788-4474-9275-50adb7b4e7e9",
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
              "id": "2663dc57-5bd4-4cdc-96bf-d903b616cf0c"
            }
          ]
        },
        {
          "id": "57be4ea3-eb64-46a4-9736-c67a11d52de7",
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
              "id": "7fe7da33-dd7b-428f-800b-3a56340d80ac"
            }
          ]
        },
        {
          "id": "a29d7b3d-0db3-4ced-85b0-2d0951477e9d",
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
              "id": "6411a8ca-8602-4f69-bf1c-5f3e4ac19fd2"
            }
          ]
        }
      ]
    }
  ]
}