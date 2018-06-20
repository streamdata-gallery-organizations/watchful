{
  "info": {
    "name": "Watchful Get Extensions For A Site",
    "_postman_id": "b9854d28-b80d-4305-9ac3-bf8cca5c7255",
    "description": "Get extensions for a site",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Extensions",
      "item": [
        {
          "id": "4fe57dfa-bd20-402c-bcfe-1e9e87c4a5bf",
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
              "id": "aeaed8a0-d8fa-41da-9bf5-dfb27fe26735"
            }
          ]
        },
        {
          "id": "13d3500f-47f1-466d-a240-8f28b48d9b63",
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
              "id": "e3787b70-09ac-45e5-8b27-0d50976bb76f"
            }
          ]
        },
        {
          "id": "11f94499-5594-4e2c-8728-6533e541f6ff",
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
              "id": "139cd32f-55a0-45ca-b9b6-b2d3e000de6d"
            }
          ]
        },
        {
          "id": "1617bb99-42b9-4c23-9be6-87f272018f1c",
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
              "id": "1136d62d-5d24-4e11-a2ce-fec141180e69"
            }
          ]
        },
        {
          "id": "3d999e68-51d5-4752-92d8-f7b178e80c94",
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
              "id": "705197fb-588c-4cf0-985e-b51cd9b16409"
            }
          ]
        }
      ]
    },
    {
      "name": "Sites",
      "item": [
        {
          "id": "3e770cc3-8c2c-4a32-bbbb-4545f5b035d3",
          "name": "sites.id.extensions.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "watchful.li",
              "path": [
                "api",
                "v1",
                "sites/:id/extensions"
              ],
              "query": [
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "limitstart",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "order",
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
            "description": "Get extensions for a site"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "281c3ffb-1e36-4a80-9b43-93428fb0b7c5"
            }
          ]
        }
      ]
    }
  ]
}