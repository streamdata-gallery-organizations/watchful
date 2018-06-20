{
  "info": {
    "name": "Watchful Update The Extension On The Remote Site",
    "_postman_id": "e32d7544-1313-4f76-8a96-a4d4853e1882",
    "description": "Update the extension on the remote site",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Extensions",
      "item": [
        {
          "id": "3f18d920-6d4e-489a-9dc2-abd0b90783a6",
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
              "id": "209f4e21-f280-4a1a-9470-46b17079663a"
            }
          ]
        },
        {
          "id": "f5334931-eb22-41be-ab1e-903135bc4403",
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
              "id": "c4e6d985-ee1e-4173-9a1d-cd45e80b9598"
            }
          ]
        },
        {
          "id": "b1c3d35e-5f95-489e-8bec-d268095c135e",
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
              "id": "33eac3d5-9a08-4fe1-8f6c-097e219ee2af"
            }
          ]
        },
        {
          "id": "144726b0-ee44-4a07-a8c8-196f469acaa5",
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
              "id": "7658aca9-bac3-48eb-a103-ff527f5dc67a"
            }
          ]
        },
        {
          "id": "8596ba08-bfdb-4627-aef3-0899b3b5330e",
          "name": "updateExtension",
          "request": {
            "url": {
              "protocol": "http",
              "host": "watchful.li",
              "path": [
                "api",
                "v1",
                "extensions/:id/update"
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
            "description": "Update the extension on the remote site"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eaf38d92-155c-439d-b4d0-4131e780dfed"
            }
          ]
        }
      ]
    }
  ]
}