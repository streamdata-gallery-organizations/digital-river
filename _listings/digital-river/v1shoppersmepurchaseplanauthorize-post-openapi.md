---
swagger: "2.0"
x-collection-name: Digital River
x-complete: 0
info:
  title: Digital River Shopper API Post Shoppers Me Purchase Plan Authorize
  description: Post shoppers me purchase plan authorize.
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
  /v1/shoppers/me/addresses/{id}:
    get:
      summary: Get Shoppers Me Addresses
      description: Get shoppers me addresses.
      operationId: getV1ShoppersMeAddresses
      x-api-path-slug: v1shoppersmeaddressesid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Resses
  /v1/shoppers/me/carts/active:
    get:
      summary: Get Shoppers Me Carts Active
      description: Get shoppers me carts active.
      operationId: getV1ShoppersMeCartsActive
      x-api-path-slug: v1shoppersmecartsactive-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
    post:
      summary: Post Shoppers Me Carts Active
      description: Post shoppers me carts active.
      operationId: postV1ShoppersMeCartsActive
      x-api-path-slug: v1shoppersmecartsactive-post
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
  /v1/shoppers/me/carts/active/apply-shipping-option:
    post:
      summary: Post Shoppers Me Carts Active Apply Shipping Option
      description: Post shoppers me carts active apply shipping option.
      operationId: postV1ShoppersMeCartsActiveApplyShippingOption
      x-api-path-slug: v1shoppersmecartsactiveapplyshippingoption-post
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Apply
      - Shipping
      - Option
  /v1/shoppers/me/carts/active/apply-shopper:
    post:
      summary: Post Shoppers Me Carts Active Apply Shopper
      description: Post shoppers me carts active apply shopper.
      operationId: postV1ShoppersMeCartsActiveApplyShopper
      x-api-path-slug: v1shoppersmecartsactiveapplyshopper-post
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Apply
      - Shopper
  /v1/shoppers/me/carts/active/billing-address:
    get:
      summary: Get Shoppers Me Carts Active Billing Address
      description: Get shoppers me carts active billing address.
      operationId: getV1ShoppersMeCartsActiveBillingAddress
      x-api-path-slug: v1shoppersmecartsactivebillingaddress-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Billing
      - Ress
    put:
      summary: Put Shoppers Me Carts Active Billing Address
      description: Put shoppers me carts active billing address.
      operationId: putV1ShoppersMeCartsActiveBillingAddress
      x-api-path-slug: v1shoppersmecartsactivebillingaddress-put
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Billing
      - Ress
  /v1/shoppers/me/carts/active/line-items:
    delete:
      summary: Delete Shoppers Me Carts Active Line Items
      description: Delete shoppers me carts active line items.
      operationId: deleteV1ShoppersMeCartsActiveLineItems
      x-api-path-slug: v1shoppersmecartsactivelineitems-delete
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Line
      - Items
    get:
      summary: Get Shoppers Me Carts Active Line Items
      description: Get shoppers me carts active line items.
      operationId: getV1ShoppersMeCartsActiveLineItems
      x-api-path-slug: v1shoppersmecartsactivelineitems-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Line
      - Items
    post:
      summary: Post Shoppers Me Carts Active Line Items
      description: Post shoppers me carts active line items.
      operationId: postV1ShoppersMeCartsActiveLineItems
      x-api-path-slug: v1shoppersmecartsactivelineitems-post
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Line
      - Items
  /v1/shoppers/me/carts/active/line-items/{id}:
    delete:
      summary: Delete Shoppers Me Carts Active Line Items
      description: Delete shoppers me carts active line items.
      operationId: deleteV1ShoppersMeCartsActiveLineItems
      x-api-path-slug: v1shoppersmecartsactivelineitemsid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Line
      - Items
    get:
      summary: Get Shoppers Me Carts Active Line Items
      description: Get shoppers me carts active line items.
      operationId: getV1ShoppersMeCartsActiveLineItems
      x-api-path-slug: v1shoppersmecartsactivelineitemsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Line
      - Items
    post:
      summary: Post Shoppers Me Carts Active Line Items
      description: Post shoppers me carts active line items.
      operationId: postV1ShoppersMeCartsActiveLineItems
      x-api-path-slug: v1shoppersmecartsactivelineitemsid-post
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Line
      - Items
  /v1/shoppers/me/carts/active/point-of-promotions/{id}/offers:
    get:
      summary: Get Shoppers Me Carts Active Point Of Promotions Offers
      description: Get shoppers me carts active point of promotions offers.
      operationId: getV1ShoppersMeCartsActivePointOfPromotionsOffers
      x-api-path-slug: v1shoppersmecartsactivepointofpromotionsidoffers-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Point
      - Promotions
      - Offers
  /v1/shoppers/me/carts/active/shipping-address:
    get:
      summary: Get Shoppers Me Carts Active Shipping Address
      description: Get shoppers me carts active shipping address.
      operationId: getV1ShoppersMeCartsActiveShippingAddress
      x-api-path-slug: v1shoppersmecartsactiveshippingaddress-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Shipping
      - Ress
    put:
      summary: Put Shoppers Me Carts Active Shipping Address
      description: Put shoppers me carts active shipping address.
      operationId: putV1ShoppersMeCartsActiveShippingAddress
      x-api-path-slug: v1shoppersmecartsactiveshippingaddress-put
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Shipping
      - Ress
  /v1/shoppers/me/carts/active/shipping-options:
    get:
      summary: Get Shoppers Me Carts Active Shipping Options
      description: Get shoppers me carts active shipping options.
      operationId: getV1ShoppersMeCartsActiveShippingOptions
      x-api-path-slug: v1shoppersmecartsactiveshippingoptions-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Shipping
      - Options
  /v1/shoppers/me/carts/active/shipping-options/{id}:
    get:
      summary: Get Shoppers Me Carts Active Shipping Options
      description: Get shoppers me carts active shipping options.
      operationId: getV1ShoppersMeCartsActiveShippingOptions
      x-api-path-slug: v1shoppersmecartsactiveshippingoptionsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Shipping
      - Options
  /v1/shoppers/me/carts/active/submit-cart:
    post:
      summary: Post Shoppers Me Carts Active Submit Cart
      description: Post shoppers me carts active submit cart.
      operationId: postV1ShoppersMeCartsActiveSubmitCart
      x-api-path-slug: v1shoppersmecartsactivesubmitcart-post
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Submit
      - Cart
  /v1/shoppers/me/carts/active/web-checkout:
    get:
      summary: Get Shoppers Me Carts Active Web Checkout
      description: Get shoppers me carts active web checkout.
      operationId: getV1ShoppersMeCartsActiveWebCheckout
      x-api-path-slug: v1shoppersmecartsactivewebcheckout-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Web
      - Checkout
    post:
      summary: Post Shoppers Me Carts Active Web Checkout
      description: Post shoppers me carts active web checkout.
      operationId: postV1ShoppersMeCartsActiveWebCheckout
      x-api-path-slug: v1shoppersmecartsactivewebcheckout-post
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Web
      - Checkout
  /v1/shoppers/me/categories:
    get:
      summary: Get Shoppers Me Categories
      description: Get shoppers me categories.
      operationId: getV1ShoppersMeCategories
      x-api-path-slug: v1shoppersmecategories-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Categories
  /v1/shoppers/me/categories/{id}:
    get:
      summary: Get Shoppers Me Categories
      description: Get shoppers me categories.
      operationId: getV1ShoppersMeCategories
      x-api-path-slug: v1shoppersmecategoriesid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Categories
  /v1/shoppers/me/categories/{id}/products:
    get:
      summary: Get Shoppers Me Categories Products
      description: Get shoppers me categories products.
      operationId: getV1ShoppersMeCategoriesProducts
      x-api-path-slug: v1shoppersmecategoriesidproducts-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Categories
      - Products
  /v1/shoppers/me/orders:
    get:
      summary: Get Shoppers Me Orders
      description: Get shoppers me orders.
      operationId: getV1ShoppersMeOrders
      x-api-path-slug: v1shoppersmeorders-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Orders
    post:
      summary: Post Shoppers Me Orders
      description: Post shoppers me orders.
      operationId: postV1ShoppersMeOrders
      x-api-path-slug: v1shoppersmeorders-post
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Orders
  /v1/shoppers/me/orders/{id}:
    get:
      summary: Get Shoppers Me Orders
      description: Get shoppers me orders.
      operationId: getV1ShoppersMeOrders
      x-api-path-slug: v1shoppersmeordersid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Orders
  /v1/shoppers/me/orders/{id}/billing-address:
    get:
      summary: Get Shoppers Me Orders Billing Address
      description: Get shoppers me orders billing address.
      operationId: getV1ShoppersMeOrdersBillingAddress
      x-api-path-slug: v1shoppersmeordersidbillingaddress-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Orders
      - Billing
      - Ress
  /v1/shoppers/me/orders/{id}/line-items:
    get:
      summary: Get Shoppers Me Orders Line Items
      description: Get shoppers me orders line items.
      operationId: getV1ShoppersMeOrdersLineItems
      x-api-path-slug: v1shoppersmeordersidlineitems-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Orders
      - Line
      - Items
  /v1/shoppers/me/orders/{id}/line-items/{lineItemId}:
    get:
      summary: Get Shoppers Me Orders Line Items Lineitemid
      description: Get shoppers me orders line items lineitemid.
      operationId: getV1ShoppersMeOrdersLineItemsLineitem
      x-api-path-slug: v1shoppersmeordersidlineitemslineitemid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: lineItemId
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Orders
      - Line
      - Items
      - Lineitemid
  /v1/shoppers/me/orders/{id}/shipping-address:
    get:
      summary: Get Shoppers Me Orders Shipping Address
      description: Get shoppers me orders shipping address.
      operationId: getV1ShoppersMeOrdersShippingAddress
      x-api-path-slug: v1shoppersmeordersidshippingaddress-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Orders
      - Shipping
      - Ress
  /v1/shoppers/me/payment-options:
    get:
      summary: Get Shoppers Me Payment Options
      description: Get shoppers me payment options.
      operationId: getV1ShoppersMePaymentOptions
      x-api-path-slug: v1shoppersmepaymentoptions-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Payment
      - Options
  /v1/shoppers/me/payment-options/{id}:
    get:
      summary: Get Shoppers Me Payment Options
      description: Get shoppers me payment options.
      operationId: getV1ShoppersMePaymentOptions
      x-api-path-slug: v1shoppersmepaymentoptionsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Payment
      - Options
  /v1/shoppers/me/point-of-promotions/{id}/offers:
    get:
      summary: Get Shoppers Me Point Of Promotions Offers
      description: Get shoppers me point of promotions offers.
      operationId: getV1ShoppersMePointOfPromotionsOffers
      x-api-path-slug: v1shoppersmepointofpromotionsidoffers-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Point
      - Promotions
      - Offers
  /v1/shoppers/me/point-of-promotions/{id}/offers/{offerId}:
    get:
      summary: Get Shoppers Me Point Of Promotions Offers Offerid
      description: Get shoppers me point of promotions offers offerid.
      operationId: getV1ShoppersMePointOfPromotionsOffersOffer
      x-api-path-slug: v1shoppersmepointofpromotionsidoffersofferid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: offerId
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Point
      - Promotions
      - Offers
      - Offerid
  /v1/shoppers/me/point-of-promotions/{id}/offers/{offerId}/product-offers:
    get:
      summary: Get Shoppers Me Point Of Promotions Offers Offerid Product Offers
      description: Get shoppers me point of promotions offers offerid product offers.
      operationId: getV1ShoppersMePointOfPromotionsOffersOfferProductOffers
      x-api-path-slug: v1shoppersmepointofpromotionsidoffersofferidproductoffers-get
      parameters:
      - in: path
        name: id
      - in: path
        name: offerId
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Point
      - Promotions
      - Offers
      - Offerid
      - Product
      - Offers
  /v1/shoppers/me/point-of-promotions/{id}/offers/{offerId}/product-offers/{productId}:
    get:
      summary: Get Shoppers Me Point Of Promotions Offers Offerid Product Offers Productid
      description: Get shoppers me point of promotions offers offerid product offers
        productid.
      operationId: getV1ShoppersMePointOfPromotionsOffersOfferProductOffersProduct
      x-api-path-slug: v1shoppersmepointofpromotionsidoffersofferidproductoffersproductid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: offerId
      - in: path
        name: productId
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Point
      - Promotions
      - Offers
      - Offerid
      - Product
      - Offers
      - Productid
  /v1/shoppers/me/product-search:
    get:
      summary: Get Shoppers Me Product Search
      description: Get shoppers me product search.
      operationId: getV1ShoppersMeProductSearch
      x-api-path-slug: v1shoppersmeproductsearch-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Product
      - Search
  /v1/shoppers/me/products:
    get:
      summary: Get Shoppers Me Products
      description: Get shoppers me products.
      operationId: getV1ShoppersMeProducts
      x-api-path-slug: v1shoppersmeproducts-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Products
  /v1/shoppers/me/products/{id}:
    get:
      summary: Get Shoppers Me Products
      description: Get shoppers me products.
      operationId: getV1ShoppersMeProducts
      x-api-path-slug: v1shoppersmeproductsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Products
  /v1/shoppers/me/products/{id}/point-of-promotions/{popId}/offers:
    get:
      summary: Get Shoppers Me Products Point Of Promotions Popid Offers
      description: Get shoppers me products point of promotions popid offers.
      operationId: getV1ShoppersMeProductsPointOfPromotionsPopOffers
      x-api-path-slug: v1shoppersmeproductsidpointofpromotionspopidoffers-get
      parameters:
      - in: path
        name: id
      - in: path
        name: popId
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Products
      - Point
      - Promotions
      - Popid
      - Offers
  /v1/shoppers/me/products/{id}/purchase:
    post:
      summary: Post Shoppers Me Products Purchase
      description: Post shoppers me products purchase.
      operationId: postV1ShoppersMeProductsPurchase
      x-api-path-slug: v1shoppersmeproductsidpurchase-post
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Products
      - Purchase
  /v1/shoppers/me/products/{id}/variations:
    get:
      summary: Get Shoppers Me Products Variations
      description: Get shoppers me products variations.
      operationId: getV1ShoppersMeProductsVariations
      x-api-path-slug: v1shoppersmeproductsidvariations-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Products
      - Variations
  /v1/shoppers/me/purchase-plan/authorize:
    post:
      summary: Post Shoppers Me Purchase Plan Authorize
      description: Post shoppers me purchase plan authorize.
      operationId: postV1ShoppersMePurchasePlanAuthorize
      x-api-path-slug: v1shoppersmepurchaseplanauthorize-post
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Purchase
      - Plan
      - Authorize
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