{
  "info": {
    "name": "Digital River Shopper API Get Shoppers Api",
    "_postman_id": "9de88398-f93c-4c72-bc81-7f9202dc214f",
    "description": "Get shoppers api.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oauth20",
      "item": [
        {
          "id": "5d518d10-3ed2-4a53-af7d-2dc1be77473c",
          "name": "getOauth20Authorize",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../oauth20/authorize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get oauth20 authorize."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09a3c503-0333-4f1f-806e-bfbaf4ee1d98"
            }
          ]
        },
        {
          "id": "4565ac44-61ac-47ac-adc7-7e15a62944b8",
          "name": "postOauth20Token",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../oauth20/token",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post oauth20 token."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "45beaf7e-9cec-42ab-bcee-5e08b1bd78ff"
            }
          ]
        }
      ]
    },
    {
      "name": "Shoppers",
      "item": [
        {
          "id": "04b679bb-d488-4fdf-909f-e80fe7161374",
          "name": "postV1Shoppers",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ed4a758-c21c-43fd-b127-eb70a9dd9a7f"
            }
          ]
        },
        {
          "id": "133ba044-7529-4797-8ccb-aad688e21be1",
          "name": "getV1ShoppersApi",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers-api",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "666db8bf-53a5-49ec-8bf8-9f9f174b624e"
            }
          ]
        }
      ]
    }
  ]
}