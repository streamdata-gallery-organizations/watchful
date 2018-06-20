{
  "info": {
    "name": "Watchful Get A List Extensions",
    "_postman_id": "7886fdc0-ac62-4751-be9d-ec12d5b2f244",
    "description": "Returns a list Extensions",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Extensions",
      "item": [
        {
          "id": "543fc66b-977a-43df-b2ac-6234f39b5554",
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
              "id": "b972c812-88bd-46dd-aa8a-23d37a7893ce"
            }
          ]
        }
      ]
    }
  ]
}