{
  "info": {
    "name": "Mota Word Get a list of supported languages",
    "_postman_id": "8f1ca432-5feb-425f-bc42-b337a551586c",
    "description": "Get a list of supported languages.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Folder",
      "item": [
        {
          "id": "68d38682-a9b9-494b-a834-d4d03404adf7",
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
              "id": "0b4277d4-9ca6-4844-9aa3-49df13b768d7"
            }
          ]
        }
      ]
    },
    {
      "name": "Formats",
      "item": [
        {
          "id": "7616ccbc-0aa5-4032-989a-8a11cb3171a0",
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
              "id": "f2647ccc-7c3d-4689-acd8-455c2e8aab2b"
            }
          ]
        }
      ]
    },
    {
      "name": "Glossary",
      "item": [
        {
          "id": "a11e0476-e68d-445e-adde-9743c8d4160f",
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
              "id": "0235131c-612c-4dd6-95a3-1dddf34114b5"
            }
          ]
        },
        {
          "id": "9f15a097-72d5-41a8-8ee2-2392dcd54954",
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
              "id": "4c0a6c33-c845-4a1c-92fa-3db9926d96d2"
            }
          ]
        }
      ]
    },
    {
      "name": "Languages",
      "item": [
        {
          "id": "90cff00a-ca05-424e-a9d7-6cb2329182a7",
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
              "id": "df8b6007-5d11-4de2-bf13-3a4f14afe172"
            }
          ]
        }
      ]
    }
  ]
}