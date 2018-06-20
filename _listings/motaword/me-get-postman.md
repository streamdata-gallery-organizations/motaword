{
  "info": {
    "name": "Mota Word Get your account information and summary.",
    "_postman_id": "3b8983ef-1a9a-40e8-91e7-4f9eb0aaa9b0",
    "description": "Get your account information and summary..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Me",
      "item": [
        {
          "id": "638f0166-882a-4745-9cd2-3344904a110a",
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
              "id": "aa17989d-7e42-428a-9d4c-8bd1edc714a5"
            }
          ]
        }
      ]
    }
  ]
}