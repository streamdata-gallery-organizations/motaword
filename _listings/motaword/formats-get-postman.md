{
  "info": {
    "name": "Mota Word Get a list of supported formats",
    "_postman_id": "a1c0b88a-e18e-42bf-be88-b739e774f287",
    "description": "Get a list of supported formats for documents, style guides and extensions.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Formats",
      "item": [
        {
          "id": "af2115fd-2ed9-458c-b343-2d5f2c4c766f",
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
              "id": "17798421-46fe-48c2-8199-1e63dee4f835"
            }
          ]
        }
      ]
    }
  ]
}