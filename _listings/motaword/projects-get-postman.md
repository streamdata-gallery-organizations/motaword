{
  "info": {
    "name": "Mota Word Get a list of your projects",
    "_postman_id": "6f7284cc-8a91-40d3-9be5-bc8426baeef8",
    "description": "Get a list of your projects.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Projects",
      "item": [
        {
          "id": "f3e47ad3-fcc3-4787-904e-2d0326847b32",
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
              "id": "cbf1272f-00a1-48db-b7a6-587ab02369d4"
            }
          ]
        }
      ]
    }
  ]
}