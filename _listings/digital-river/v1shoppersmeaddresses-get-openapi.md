---
swagger: "2.0"
x-collection-name: Digital River
x-complete: 0
info:
  title: Digital River Shopper API Get Shoppers Me Addresses
  description: Get shoppers me addresses.
  version: v1
host: store.digitalriver.com
basePath: /store/{mysite}
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /oauth20/authorize:
    get:
      summary: Get Oauth20 Authorize
      description: Get oauth20 authorize.
      operationId: getOauth20Authorize
      x-api-path-slug: oauth20authorize-get
      responses:
        200:
          description: OK
      tags:
      - Oauth20
      - Authorize
  /oauth20/token:
    post:
      summary: Post Oauth20 Token
      description: Post oauth20 token.
      operationId: postOauth20Token
      x-api-path-slug: oauth20token-post
      responses:
        200:
          description: OK
      tags:
      - Oauth20
      - Token
  /v1/shoppers:
    post:
      summary: Post Shoppers
      description: Post shoppers.
      operationId: postV1Shoppers
      x-api-path-slug: v1shoppers-post
      responses:
        200:
          description: OK
      tags:
      - Shoppers
  /v1/shoppers-api:
    get:
      summary: Get Shoppers Api
      description: Get shoppers api.
      operationId: getV1ShoppersApi
      x-api-path-slug: v1shoppersapi-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Api
  /v1/shoppers/me:
    get:
      summary: Get Shoppers Me
      description: Get shoppers me.
      operationId: getV1ShoppersMe
      x-api-path-slug: v1shoppersme-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
    post:
      summary: Post Shoppers Me
      description: Post shoppers me.
      operationId: postV1ShoppersMe
      x-api-path-slug: v1shoppersme-post
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
  /v1/shoppers/me/account:
    get:
      summary: Get Shoppers Me Account
      description: Get shoppers me account.
      operationId: getV1ShoppersMeAccount
      x-api-path-slug: v1shoppersmeaccount-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Account
  /v1/shoppers/me/addresses:
    get:
      summary: Get Shoppers Me Addresses
      description: Get shoppers me addresses.
      operationId: getV1ShoppersMeAddresses
      x-api-path-slug: v1shoppersmeaddresses-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Resses
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---