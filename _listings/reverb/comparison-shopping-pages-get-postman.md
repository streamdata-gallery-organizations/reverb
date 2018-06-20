{
  "info": {
    "name": "reverb Get Comparison Shopping Pages",
    "_postman_id": "8ea4a864-4d36-413f-9cab-d2a5eb5cced1",
    "description": "Returns a set of comparison shopping pages based on the current params",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Comparison",
      "item": [
        {
          "id": "2d4c8a79-d085-4e11-ab72-75fa29996e1d",
          "name": "getComparisonShoppingPages",
          "request": {
            "url": "http://api.reverb.com/api/comparison_shopping_pages",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a set of comparison shopping pages based on the current params"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eeed9792-3131-4771-a861-3a29b2510667"
            }
          ]
        }
      ]
    }
  ]
}