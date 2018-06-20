{
  "info": {
    "name": "Digital River Shopper API Post Shoppers",
    "_postman_id": "4ab809f6-258e-46fa-9fd2-730faf20ba86",
    "description": "Post shoppers.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oauth20",
      "item": [
        {
          "id": "907b033a-8be5-4340-8971-231e237e22a1",
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
              "id": "26247cb3-420f-4f0f-88ed-af9bd829d347"
            }
          ]
        },
        {
          "id": "1110fd6c-b56e-4a9b-b3d0-75ca661c573b",
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
              "id": "38f2be04-9030-48ca-a65a-511d5119432b"
            }
          ]
        }
      ]
    },
    {
      "name": "Shoppers",
      "item": [
        {
          "id": "46dc922f-dd60-4e75-bb59-bc4bcf267b33",
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
              "id": "adc3f9c2-38f6-4f38-bff5-645e5512aea8"
            }
          ]
        }
      ]
    }
  ]
}