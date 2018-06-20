---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: reverb Get Listings Listing Bump
  description: View available bump tiers and stats for a listing
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /articles:
    get:
      summary: Get Articles
      description: Get articles.
      operationId: getArticles
      x-api-path-slug: articles-get
      parameters:
      - in: query
        name: exclude_featured
        description: Number of featured articles to exclude
      - in: query
        name: offset
      - in: query
        name: page
      - in: query
        name: per_page
      - in: query
        name: query
        description: Whats being searched for
      responses:
        200:
          description: OK
      tags:
      - Articles
  /categories:
    get:
      summary: Get Categories
      description: List of supported product categories
      operationId: getCategories
      x-api-path-slug: categories-get
      responses:
        200:
          description: OK
      tags:
      - Categories
  /categories/flat:
    get:
      summary: Get Categories Flat
      description: Get categories flat.
      operationId: getCategoriesFlat
      x-api-path-slug: categoriesflat-get
      responses:
        200:
          description: OK
      tags:
      - Categories
      - Flat
  /categories/taxonomy:
    get:
      summary: Get Categories Taxonomy
      description: Full taxonomy tree of categories including middle categories
      operationId: getCategoriesTaxonomy
      x-api-path-slug: categoriestaxonomy-get
      responses:
        200:
          description: OK
      tags:
      - Categories
      - Taxonomy
  /categories/{product_type}/{category}:
    get:
      summary: Get Categories Product Type Category
      description: Get categories product type category.
      operationId: getCategoriesProductTypeCategory
      x-api-path-slug: categoriesproduct-typecategory-get
      parameters:
      - in: path
        name: category
      - in: path
        name: product_type
      responses:
        200:
          description: OK
      tags:
      - Categories
      - Product
      - Type
      - Category
  /categories/{uuid}:
    get:
      summary: Get Categories Uu
      description: Get category details
      operationId: getCategoriesUu
      x-api-path-slug: categoriesuuid-get
      parameters:
      - in: path
        name: uuid
      responses:
        200:
          description: OK
      tags:
      - Categories
      - Uuid
  /comparison_shopping_pages:
    get:
      summary: Get Comparison Shopping Pages
      description: Returns a set of comparison shopping pages based on the current
        params
      operationId: getComparisonShoppingPages
      x-api-path-slug: comparison-shopping-pages-get
      responses:
        200:
          description: OK
      tags:
      - Comparison
      - Shopping
      - Pages
  /comparison_shopping_pages/find:
    get:
      summary: Get Comparison Shopping Pages Find
      description: Get comparison shopping pages find.
      operationId: getComparisonShoppingPagesFind
      x-api-path-slug: comparison-shopping-pagesfind-get
      parameters:
      - in: query
        name: id
        description: ID of the comparison shopping page
      - in: query
        name: slug
        description: Slug of the comparison shopping page
      responses:
        200:
          description: OK
      tags:
      - Comparison
      - Shopping
      - Pages
      - Find
  /comparison_shopping_pages/{id}:
    get:
      summary: Get Comparison Shopping Pages
      description: Get comparison shopping pages.
      operationId: getComparisonShoppingPages
      x-api-path-slug: comparison-shopping-pagesid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Comparison
      - Shopping
      - Pages
      - Id
  /comparison_shopping_pages/{id}/listings:
    get:
      summary: Get Comparison Shopping Pages Listings
      description: Return new or used listings for a comparison shopping page
      operationId: getComparisonShoppingPagesListings
      x-api-path-slug: comparison-shopping-pagesidlistings-get
      parameters:
      - in: query
        name: condition
        description: Condition of the listing
      - in: path
        name: id
      - in: query
        name: offset
      - in: query
        name: page
      - in: query
        name: per_page
      responses:
        200:
          description: OK
      tags:
      - Comparison
      - Shopping
      - Pages
      - Id
      - Listings
  /comparison_shopping_pages/{id}/reviews:
    get:
      summary: Get Comparison Shopping Pages Reviews
      description: View reviews of a comparison shopping page
      operationId: getComparisonShoppingPagesReviews
      x-api-path-slug: comparison-shopping-pagesidreviews-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Comparison
      - Shopping
      - Pages
      - Id
      - Reviews
  /conversations/{conversation_id}/offer:
    post:
      summary: Post Conversations Conversation Offer
      description: Make an offer to the other participant in the conversation
      operationId: postConversationsConversationOffer
      x-api-path-slug: conversationsconversation-idoffer-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: conversation_id
      responses:
        200:
          description: OK
      tags:
      - Conversations
      - Conversation
      - Id
      - Offer
  /conversations/{id}/offer:
    post:
      summary: Post Conversations Offer
      description: Make an offer to the other participant in the conversation
      operationId: postConversationsOffer
      x-api-path-slug: conversationsidoffer-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Conversations
      - Id
      - Offer
  /countries:
    get:
      summary: Get Countries
      description: Retrieve a list of country codes with corresponding subregions
      operationId: getCountries
      x-api-path-slug: countries-get
      responses:
        200:
          description: OK
      tags:
      - Countries
  /csps:
    get:
      summary: Get Csps
      description: Returns a set of comparison shopping pages based on the current
        params
      operationId: getCsps
      x-api-path-slug: csps-get
      responses:
        200:
          description: OK
      tags:
      - Csps
  /csps/categories:
    get:
      summary: Get Csps Categories
      description: Get csps categories.
      operationId: getCspsCategories
      x-api-path-slug: cspscategories-get
      responses:
        200:
          description: OK
      tags:
      - Csps
      - Categories
  /curated_sets/{slug}:
    get:
      summary: Get Curated Sets Slug
      description: Get curated sets slug.
      operationId: getCuratedSetsSlug
      x-api-path-slug: curated-setsslug-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Curated
      - Sets
      - Slug
  /currencies/display:
    get:
      summary: Get Currencies Display
      description: List of supported display currencies for browsing listings
      operationId: getCurrenciesDisplay
      x-api-path-slug: currenciesdisplay-get
      responses:
        200:
          description: OK
      tags:
      - Currencies
      - Display
  /currencies/listing:
    get:
      summary: Get Currencies Listing
      description: List of supported listing currencies for shops
      operationId: getCurrenciesListing
      x-api-path-slug: currencieslisting-get
      responses:
        200:
          description: OK
      tags:
      - Currencies
      - Listing
  /feedback/{feedback_id}:
    get:
      summary: Get Feedback Feedback
      description: Get feedback feedback.
      operationId: getFeedbackFeedback
      x-api-path-slug: feedbackfeedback-id-get
      parameters:
      - in: path
        name: feedback_id
      responses:
        200:
          description: OK
      tags:
      - Feedback
      - Feedback
      - Id
  /handpicked/{slug}:
    get:
      summary: Get Handpicked Slug
      description: Get results from a handpicked collection
      operationId: getHandpickedSlug
      x-api-path-slug: handpickedslug-get
      parameters:
      - in: query
        name: accepts_gift_cards
        description: If true, include only items that accept gift cards
      - in: query
        name: accepts_payment_plans
        description: If true, only show items that can be purchased with a payment
          plan
      - in: query
        name: auction_price_max
        description: Maximum current auction price
      - in: query
        name: category
        description: Category slug from /api/categories
      - in: query
        name: conditions
        description: 'Condition: all,new,b-stock,used,non-functioning'
      - in: query
        name: currency
        description: The currency to be used for the price filters
      - in: query
        name: decade
        description: 'Decade: e'
      - in: query
        name: exclude_auctions
        description: If true, exclude auctions
      - in: query
        name: finish
        description: Visual finish of the item, common for guitars
      - in: query
        name: handmade
        description: Handmade items only
      - in: query
        name: item_city
        description: City where item is located
      - in: query
        name: item_country
        description: DEPRECATED - Country code where item is located
      - in: query
        name: item_region
        description: Country code where item is located
      - in: query
        name: item_state
        description: State or region code where item is located
      - in: query
        name: listing_type
        description: 'Type of listing: auctions,offers'
      - in: query
        name: make
        description: Make(s)/brand of item (e
      - in: query
        name: model
        description: Model of item (e
      - in: query
        name: must_not
        description: Search term negation
      - in: query
        name: not_ids
        description: Listing ID negation
      - in: query
        name: offset
      - in: query
        name: page
      - in: query
        name: per_page
      - in: query
        name: preferred_seller
        description: If true, include only items by Reverb Preferred Sellers
      - in: query
        name: price_max
        description: Maximum price of search results (USD)
      - in: query
        name: price_min
        description: Minimum price of search results (USD)
      - in: query
        name: product_type
        description: Product type slug from /api/categories
      - in: query
        name: query
        description: Search query
      - in: query
        name: ships_to
        description: Limit search to items that ship to this country code
      - in: query
        name: shop
        description: Slug of shop to search
      - in: query
        name: shop_id
        description: ID of shop to search
      - in: path
        name: slug
      - in: query
        name: watchers_count_min
        description: Minimum number of watchers (used to find popular items)
      - in: query
        name: year_max
        description: Maximum year of manufacture
      - in: query
        name: year_min
        description: Minumum year of manufacture
      responses:
        200:
          description: OK
      tags:
      - Handpicked
      - Slug
  /listing_conditions:
    get:
      summary: Get Listing Conditions
      description: List of supported product conditions
      operationId: getListingConditions
      x-api-path-slug: listing-conditions-get
      responses:
        200:
          description: OK
      tags:
      - Listing
      - Conditions
  /listings:
    get:
      summary: Get Listings
      description: Default search of listings includes only used & handmade. Add a
        filter to view all listings or use the /listings/all endpoint.
      operationId: getListings
      x-api-path-slug: listings-get
      parameters:
      - in: query
        name: accepts_gift_cards
        description: If true, include only items that accept gift cards
      - in: query
        name: accepts_payment_plans
        description: If true, only show items that can be purchased with a payment
          plan
      - in: query
        name: auction_price_max
        description: Maximum current auction price
      - in: query
        name: category
        description: Category slug from /api/categories
      - in: query
        name: conditions
        description: 'Condition: all,new,b-stock,used,non-functioning'
      - in: query
        name: currency
        description: The currency to be used for the price filters
      - in: query
        name: decade
        description: 'Decade: e'
      - in: query
        name: exclude_auctions
        description: If true, exclude auctions
      - in: query
        name: finish
        description: Visual finish of the item, common for guitars
      - in: query
        name: handmade
        description: Handmade items only
      - in: query
        name: item_city
        description: City where item is located
      - in: query
        name: item_country
        description: DEPRECATED - Country code where item is located
      - in: query
        name: item_region
        description: Country code where item is located
      - in: query
        name: item_state
        description: State or region code where item is located
      - in: query
        name: listing_type
        description: 'Type of listing: auctions,offers'
      - in: query
        name: make
        description: Make(s)/brand of item (e
      - in: query
        name: model
        description: Model of item (e
      - in: query
        name: must_not
        description: Search term negation
      - in: query
        name: not_ids
        description: Listing ID negation
      - in: query
        name: offset
      - in: query
        name: page
      - in: query
        name: per_page
      - in: query
        name: preferred_seller
        description: If true, include only items by Reverb Preferred Sellers
      - in: query
        name: price_max
        description: Maximum price of search results (USD)
      - in: query
        name: price_min
        description: Minimum price of search results (USD)
      - in: query
        name: product_type
        description: Product type slug from /api/categories
      - in: query
        name: query
        description: Search query
      - in: query
        name: ships_to
        description: Limit search to items that ship to this country code
      - in: query
        name: shop
        description: Slug of shop to search
      - in: query
        name: shop_id
        description: ID of shop to search
      - in: query
        name: watchers_count_min
        description: Minimum number of watchers (used to find popular items)
      - in: query
        name: year_max
        description: Maximum year of manufacture
      - in: query
        name: year_min
        description: Minumum year of manufacture
      responses:
        200:
          description: OK
      tags:
      - Listings
    post:
      summary: Post Listings
      description: Create a listing
      operationId: postListings
      x-api-path-slug: listings-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Listings
  /listings/all:
    get:
      summary: Get Listings All
      description: All listings including used, handmade, and brand new
      operationId: getListingsAll
      x-api-path-slug: listingsall-get
      parameters:
      - in: query
        name: accepts_gift_cards
        description: If true, include only items that accept gift cards
      - in: query
        name: accepts_payment_plans
        description: If true, only show items that can be purchased with a payment
          plan
      - in: query
        name: auction_price_max
        description: Maximum current auction price
      - in: query
        name: category
        description: Category slug from /api/categories
      - in: query
        name: conditions
        description: 'Condition: all,new,b-stock,used,non-functioning'
      - in: query
        name: currency
        description: The currency to be used for the price filters
      - in: query
        name: decade
        description: 'Decade: e'
      - in: query
        name: exclude_auctions
        description: If true, exclude auctions
      - in: query
        name: finish
        description: Visual finish of the item, common for guitars
      - in: query
        name: handmade
        description: Handmade items only
      - in: query
        name: item_city
        description: City where item is located
      - in: query
        name: item_country
        description: DEPRECATED - Country code where item is located
      - in: query
        name: item_region
        description: Country code where item is located
      - in: query
        name: item_state
        description: State or region code where item is located
      - in: query
        name: listing_type
        description: 'Type of listing: auctions,offers'
      - in: query
        name: make
        description: Make(s)/brand of item (e
      - in: query
        name: model
        description: Model of item (e
      - in: query
        name: must_not
        description: Search term negation
      - in: query
        name: not_ids
        description: Listing ID negation
      - in: query
        name: offset
      - in: query
        name: page
      - in: query
        name: per_page
      - in: query
        name: preferred_seller
        description: If true, include only items by Reverb Preferred Sellers
      - in: query
        name: price_max
        description: Maximum price of search results (USD)
      - in: query
        name: price_min
        description: Minimum price of search results (USD)
      - in: query
        name: product_type
        description: Product type slug from /api/categories
      - in: query
        name: query
        description: Search query
      - in: query
        name: ships_to
        description: Limit search to items that ship to this country code
      - in: query
        name: shop
        description: Slug of shop to search
      - in: query
        name: shop_id
        description: ID of shop to search
      - in: query
        name: watchers_count_min
        description: Minimum number of watchers (used to find popular items)
      - in: query
        name: year_max
        description: Maximum year of manufacture
      - in: query
        name: year_min
        description: Minumum year of manufacture
      responses:
        200:
          description: OK
      tags:
      - Listings
  /listings/facets/seller_location:
    get:
      summary: Get Listings Facets Seller Location
      description: Get listings facets seller location.
      operationId: getListingsFacetsSellerLocation
      x-api-path-slug: listingsfacetsseller-location-get
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Facets
      - Seller
      - Location
  /listings/{id}/negotiation:
    get:
      summary: Get Listings Negotiation
      description: Returns the latest negotiation for the requesting user given a
        listing id
      operationId: getListingsNegotiation
      x-api-path-slug: listingsidnegotiation-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Id
      - Negotiation
  /listings/{id}/offer:
    post:
      summary: Post Listings Offer
      description: Make an offer to the seller of a listing
      operationId: postListingsOffer
      x-api-path-slug: listingsidoffer-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Id
      - Offer
  /listings/{listing_id}/bump:
    get:
      summary: Get Listings Listing Bump
      description: View available bump tiers and stats for a listing
      operationId: getListingsListingBump
      x-api-path-slug: listingslisting-idbump-get
      parameters:
      - in: path
        name: listing_id
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Listing
      - Id
      - Bump
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