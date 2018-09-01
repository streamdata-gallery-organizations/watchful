{
  "info": {
    "name": "Watchful Install Extension",
    "_postman_id": "51caf3ca-0579-4433-9700-1524ebfabe02",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Extensions",
      "item": [
        {
          "id": "eef84b08-e7db-45c7-a97a-a7cf7a3353ac",
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
              "id": "97e1475b-7228-43a0-9854-d58e96697a33"
            }
          ]
        },
        {
          "id": "99a084ed-8182-4ed4-8a7f-bf86b0a361e4",
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
              "id": "c704bfaf-ffdf-4352-b5e2-bb796344c3d5"
            }
          ]
        },
        {
          "id": "227c2f6f-aeb9-43f0-824b-63b3c6187b1e",
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
              "id": "8d9a7ada-9e13-4ac4-8b30-43f81a5a2393"
            }
          ]
        },
        {
          "id": "06e99355-d333-4129-9440-ce72b6cfd28e",
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
              "id": "a29ae9ab-5e6d-4686-b11a-2aaf7bb88d9e"
            }
          ]
        },
        {
          "id": "20e8eb4c-cefc-4456-82e1-7615ca388893",
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
              "id": "b3f72c01-e4ce-4fba-b4ca-a4ce2a6f0949"
            }
          ]
        }
      ]
    },
    {
      "name": "Sites",
      "item": [
        {
          "id": "402c7375-85fe-4cbc-8444-101b01b1cac7",
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
              "id": "10f1bfd4-fd77-495a-aaf4-08aa4dad1343"
            }
          ]
        },
        {
          "id": "3a194aad-1473-4ba1-8abe-b5fa11025cce",
          "name": "installExtension",
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
                  "key": "url",
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Install Extension"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0102f5ea-901f-4fd5-9253-6e7ea27b4c8e"
            }
          ]
        }
      ]
    }
  ]
}