{
  "info": {
    "name": "Watchful Remove 'ignore Updates' For A Given Extension",
    "_postman_id": "f071d411-da2b-4465-bba9-4f39edc9bdcc",
    "description": "Remove 'ignore updates' for a given extension",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Extensions",
      "item": [
        {
          "id": "30ba5b8d-e74e-479c-b28c-f24dcfc8cafa",
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
              "id": "6c39ee40-fafa-47c8-ba45-1c385750fca0"
            }
          ]
        },
        {
          "id": "443367e5-823b-4949-9246-afd57dc060f2",
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
              "id": "706c04df-99e2-432d-b35b-111a2f0e36ee"
            }
          ]
        },
        {
          "id": "d533564f-2549-4167-b247-366e4e4306cc",
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
              "id": "2abb6834-358b-446f-afa0-e31e6d7ccecc"
            }
          ]
        },
        {
          "id": "73958e61-93b6-492c-a735-1680cbcced04",
          "name": "unignoreExtensionUpdate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "watchful.li",
              "path": [
                "api",
                "v1",
                "extensions/:id/unignore"
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
            "description": "Remove 'ignore updates' for a given extension"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5a12712a-7b38-4905-9425-a08955a09a1b"
            }
          ]
        }
      ]
    }
  ]
}