{
  "info": {
    "name": "Google Cloud Storage Get Buckets",
    "_postman_id": "86af26db-5c01-4d36-b5bf-fafe45b0a328",
    "description": "Retrieves a list of buckets for a given project.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Bucket",
      "item": [
        {
          "id": "72440fd7-dafd-4899-8dbc-37a3974fca62",
          "name": "storage.buckets.list",
          "request": {
            "url": "http://example.com/api/b?maxResults=%7B%7D&pageToken=%7B%7D&prefix=%7B%7D&project=%7B%7D&projection=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a list of buckets for a given project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "49b00b5b-7873-4df0-8615-276a9b867b68"
            }
          ]
        }
      ]
    }
  ]
}