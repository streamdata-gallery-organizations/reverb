{
  "info": {
    "name": "reverb Get Comparison Shopping Pages",
    "_postman_id": "e6a01c0c-3a58-46dc-b9c9-dd49d9ddf862",
    "description": "Get comparison shopping pages.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Comparison",
      "item": [
        {
          "id": "bf89c30c-ac34-4cce-835f-93305adb083a",
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
              "id": "dd360b7d-9d8a-468b-b65f-6c616a49bfef"
            }
          ]
        },
        {
          "id": "ecb8293d-9d06-4214-a4f2-bca4a6fbfec2",
          "name": "getComparisonShoppingPagesFind",
          "request": {
            "url": "http://api.reverb.com/api/comparison_shopping_pages/find?id=%7B%7D&slug=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get comparison shopping pages find."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f72af24-c427-4ca6-935d-effbaafab086"
            }
          ]
        },
        {
          "id": "b629e981-c0ce-41dc-8b31-62d48b9a4ec4",
          "name": "getComparisonShoppingPages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "comparison_shopping_pages/:id"
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
            "description": "Get comparison shopping pages."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6bc9e22-24b4-486a-a0ea-6784887f97b5"
            }
          ]
        }
      ]
    }
  ]
}