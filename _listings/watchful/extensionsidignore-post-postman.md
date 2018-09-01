{
  "info": {
    "name": "Watchful Set 'ignore Updates' For A Given Extension / Site_id",
    "_postman_id": "a7b5f65c-4e2a-4fe3-8769-37c0ad9923f6",
    "description": "Set 'ignore updates' for a given extension / site_id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Extensions",
      "item": [
        {
          "id": "4303d5c5-be66-4c81-b014-0c76439c8ed3",
          "name": "getExtensions",
          "request": {
            "url": "http://watchful.li/api/v1/extensions?ext_name=%7B%7D&ext_prefix=%7B%7D&fields=%7B%7D&limit=%7B%7D&limitstart=%7B%7D&order=%7B%7D&siteids=%7B%7D&version=%7B%7D&vUpdate=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list Extensions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "79b8752a-b8c6-4440-8a8e-6e669cd689ea"
            }
          ]
        },
        {
          "id": "0b673af2-5287-4785-82ea-48b544e81719",
          "name": "getFieldsExtensions",
          "request": {
            "url": "http://watchful.li/api/v1/extensions/metadata",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of fields"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f331f567-87e4-46ee-83cf-df65acda61f2"
            }
          ]
        },
        {
          "id": "4649685a-1f76-4802-9457-adaa33cb5cec",
          "name": "ignoreExtensionUpdate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "watchful.li",
              "path": [
                "api",
                "v1",
                "extensions/:id/ignore"
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
            "description": "Set 'ignore updates' for a given extension / site_id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e093b6ba-da2f-478b-bc06-72d2754b1685"
            }
          ]
        }
      ]
    }
  ]
}