{
  "info": {
    "name": "Bands in Town Get artist information",
    "_postman_id": "2d44cc70-9692-4ce7-81bf-5a2635aad167",
    "description": "Get artist information",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Bands",
      "item": [
        {
          "id": "316310fe-9417-418a-9674-17b270b2a2a4",
          "name": "artist",
          "request": {
            "url": {
              "protocol": "http",
              "host": "rest.bandsintown.com",
              "path": [
                "artists/:artistname"
              ],
              "query": [
                {
                  "key": "app_id",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "artistname",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get artist information"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "085d118c-3e78-4d5c-bc13-91084cb1c2d4"
            }
          ]
        }
      ]
    }
  ]
}