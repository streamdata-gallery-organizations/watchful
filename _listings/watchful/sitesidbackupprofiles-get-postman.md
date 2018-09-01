{
  "info": {
    "name": "Watchful Return Backup Profile",
    "_postman_id": "223152f0-f3ba-4b14-a394-f7c5a4946d78",
    "description": "Return backup profile",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Sites",
      "item": [
        {
          "id": "95dd59b6-5cd6-49a9-86bb-12017baf332d",
          "name": "getBackupProfiles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "watchful.li",
              "path": [
                "api",
                "v1",
                "sites/:id/backupprofiles"
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
            "description": "Return backup profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bfc0289c-8e7b-4d3a-a26c-4a208cc3b4a1"
            }
          ]
        }
      ]
    }
  ]
}