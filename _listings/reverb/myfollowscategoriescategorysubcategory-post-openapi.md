---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: reverb Post My Follows Categories Category Subcategory
  description: Post my follows categories category subcategory.
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
  /listings/{listing_id}/bump/{budget_type}:
    post:
      summary: Post Listings Listing Bump Budget Type
      description: Post listings listing bump budget type.
      operationId: postListingsListingBumpBudgetType
      x-api-path-slug: listingslisting-idbumpbudget-type-post
      parameters:
      - in: path
        name: budget_type
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
      - Budget
      - Type
  /listings/{listing_id}/conversations:
    post:
      summary: Post Listings Listing Conversations
      description: Post listings listing conversations.
      operationId: postListingsListingConversations
      x-api-path-slug: listingslisting-idconversations-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: listing_id
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Listing
      - Id
      - Conversations
  /listings/{listing_id}/images:
    get:
      summary: Get Listings Listing Images
      description: View the images associated with a particular listing
      operationId: getListingsListingImages
      x-api-path-slug: listingslisting-idimages-get
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
      - Images
  /listings/{listing_id}/images/{image_id}:
    delete:
      summary: Delete Listings Listing Images Image
      description: Delete listings listing images image.
      operationId: deleteListingsListingImagesImage
      x-api-path-slug: listingslisting-idimagesimage-id-delete
      parameters:
      - in: path
        name: image_id
      - in: path
        name: listing_id
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Listing
      - Id
      - Images
      - Image
      - Id
  /listings/{listing_id}/product_bundle:
    get:
      summary: Get Listings Listing Product Bundle
      description: Find a product bundle attached to a listing
      operationId: getListingsListingProductBundle
      x-api-path-slug: listingslisting-idproduct-bundle-get
      parameters:
      - in: query
        name: for_seller
        description: Pass to see non-live bundles as the seller
      - in: path
        name: listing_id
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Listing
      - Id
      - Product
      - Bundle
  /listings/{listing_id}/sales:
    get:
      summary: Get Listings Listing Sales
      description: See all sales that include a listing.
      operationId: getListingsListingSales
      x-api-path-slug: listingslisting-idsales-get
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
      - Sales
  /listings/{slug}:
    delete:
      summary: Delete Listings Slug
      description: Delete a draft listing. Cannot be used on non-drafts.
      operationId: deleteListingsSlug
      x-api-path-slug: listingsslug-delete
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Slug
    get:
      summary: Get Listings Slug
      description: Get listings slug.
      operationId: getListingsSlug
      x-api-path-slug: listingsslug-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Slug
    put:
      summary: Put Listings Slug
      description: Put listings slug.
      operationId: putListingsSlug
      x-api-path-slug: listingsslug-put
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Slug
  /listings/{slug}/edit:
    get:
      summary: Get Listings Slug Edit
      description: Get listings slug edit.
      operationId: getListingsSlugEdit
      x-api-path-slug: listingsslugedit-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Slug
      - Edit
  /listings/{slug}/flag:
    post:
      summary: Post Listings Slug Flag
      description: Flag a listing for inappropriate content or fraud
      operationId: postListingsSlugFlag
      x-api-path-slug: listingsslugflag-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Slug
      - Flag
  /listings/{slug}/reviews:
    get:
      summary: Get Listings Slug Reviews
      description: Get listings slug reviews.
      operationId: getListingsSlugReviews
      x-api-path-slug: listingsslugreviews-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Slug
      - Reviews
    post:
      summary: Post Listings Slug Reviews
      description: Create a review for a listing
      operationId: postListingsSlugReviews
      x-api-path-slug: listingsslugreviews-post
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Slug
      - Reviews
  /listings/{slug}/similar_listings:
    get:
      summary: Get Listings Slug Similar Listings
      description: Get listings slug similar listings.
      operationId: getListingsSlugSimilarListings
      x-api-path-slug: listingsslugsimilar-listings-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Slug
      - Similar
      - Listings
  /my/account:
    get:
      summary: Get My Account
      description: Get account details
      operationId: getMyAccount
      x-api-path-slug: myaccount-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Account
    put:
      summary: Put My Account
      description: Update account details
      operationId: putMyAccount
      x-api-path-slug: myaccount-put
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
      - My
      - Account
  /my/addresses:
    get:
      summary: Get My Addresses
      description: See all addresses in your address book
      operationId: getMyAddresses
      x-api-path-slug: myaddresses-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Addresses
    post:
      summary: Post My Addresses
      description: Create a new address in your address book
      operationId: postMyAddresses
      x-api-path-slug: myaddresses-post
      responses:
        200:
          description: OK
      tags:
      - My
      - Addresses
  /my/addresses/{address_id}:
    delete:
      summary: Delete My Addresses Address
      description: Delete an existing address in your address book
      operationId: deleteMyAddressesAddress
      x-api-path-slug: myaddressesaddress-id-delete
      parameters:
      - in: path
        name: address_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Addresses
      - Address
      - Id
    put:
      summary: Put My Addresses Address
      description: Update an existing address in your address book
      operationId: putMyAddressesAddress
      x-api-path-slug: myaddressesaddress-id-put
      parameters:
      - in: path
        name: address_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Addresses
      - Address
      - Id
  /my/conversations:
    get:
      summary: Get My Conversations
      description: Get a list of your conversations
      operationId: getMyConversations
      x-api-path-slug: myconversations-get
      parameters:
      - in: query
        name: offset
      - in: query
        name: page
      - in: query
        name: per_page
      - in: query
        name: search
        description: Query string to search conversations by
      - in: query
        name: unread_only
        description: Show unread conversations only
      responses:
        200:
          description: OK
      tags:
      - My
      - Conversations
    post:
      summary: Post My Conversations
      description: Post my conversations.
      operationId: postMyConversations
      x-api-path-slug: myconversations-post
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
      - My
      - Conversations
  /my/conversations/{conversation_id}/messages:
    post:
      summary: Post My Conversations Conversation Messages
      description: Post my conversations conversation messages.
      operationId: postMyConversationsConversationMessages
      x-api-path-slug: myconversationsconversation-idmessages-post
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
      - My
      - Conversations
      - Conversation
      - Id
      - Messages
  /my/conversations/{id}:
    get:
      summary: Get My Conversations
      description: Display conversation details with messages in natural time order
        (oldest to newest)
      operationId: getMyConversations
      x-api-path-slug: myconversationsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - My
      - Conversations
      - Id
    put:
      summary: Put My Conversations
      description: Mark a conversation read/unread
      operationId: putMyConversations
      x-api-path-slug: myconversationsid-put
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
      - My
      - Conversations
      - Id
  /my/counts:
    get:
      summary: Get My Counts
      description: Get your actionable status counts
      operationId: getMyCounts
      x-api-path-slug: mycounts-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Counts
  /my/curated_set/product/{product_id}:
    delete:
      summary: Delete My Curated Set Product Product
      description: Delete my curated set product product.
      operationId: deleteMyCuratedSetProductProduct
      x-api-path-slug: mycurated-setproductproduct-id-delete
      parameters:
      - in: path
        name: product_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Curated
      - Set
      - Product
      - Product
      - Id
    post:
      summary: Post My Curated Set Product Product
      description: Post my curated set product product.
      operationId: postMyCuratedSetProductProduct
      x-api-path-slug: mycurated-setproductproduct-id-post
      parameters:
      - in: path
        name: product_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Curated
      - Set
      - Product
      - Product
      - Id
  /my/feed:
    get:
      summary: Get My Feed
      description: Get listings from your feed
      operationId: getMyFeed
      x-api-path-slug: myfeed-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Feed
  /my/feed/customize:
    get:
      summary: Get My Feed Customize
      description: get your feed customization options
      operationId: getMyFeedCustomize
      x-api-path-slug: myfeedcustomize-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Feed
      - Customize
  /my/feed/grid:
    get:
      summary: Get My Feed Gr
      description: Get my feed gr.
      operationId: getMyFeedGr
      x-api-path-slug: myfeedgrid-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Feed
      - Grid
  /my/feedback/received:
    get:
      summary: Get My Feedback Received
      description: List of received feedback
      operationId: getMyFeedbackReceived
      x-api-path-slug: myfeedbackreceived-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Feedback
      - Received
  /my/feedback/sent:
    get:
      summary: Get My Feedback Sent
      description: List of sent feedback
      operationId: getMyFeedbackSent
      x-api-path-slug: myfeedbacksent-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Feedback
      - Sent
  /my/follows:
    get:
      summary: Get My Follows
      description: See what the user is following
      operationId: getMyFollows
      x-api-path-slug: myfollows-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
  /my/follows/articles:
    get:
      summary: Get My Follows Articles
      description: Returns a user's ArticleCategoryFollows
      operationId: getMyFollowsArticles
      x-api-path-slug: myfollowsarticles-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Articles
    post:
      summary: Post My Follows Articles
      description: Set a user's ArticleCategoryFollows
      operationId: postMyFollowsArticles
      x-api-path-slug: myfollowsarticles-post
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
      - My
      - Follows
      - Articles
  /my/follows/brands/{slug}:
    delete:
      summary: Delete My Follows Brands Slug
      description: Delete my follows brands slug.
      operationId: deleteMyFollowsBrandsSlug
      x-api-path-slug: myfollowsbrandsslug-delete
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Brands
      - Slug
    get:
      summary: Get My Follows Brands Slug
      description: Get my follows brands slug.
      operationId: getMyFollowsBrandsSlug
      x-api-path-slug: myfollowsbrandsslug-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Brands
      - Slug
    post:
      summary: Post My Follows Brands Slug
      description: Post my follows brands slug.
      operationId: postMyFollowsBrandsSlug
      x-api-path-slug: myfollowsbrandsslug-post
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Brands
      - Slug
  /my/follows/categories/{category}/{subcategory}:
    delete:
      summary: Delete My Follows Categories Category Subcategory
      description: Delete my follows categories category subcategory.
      operationId: deleteMyFollowsCategoriesCategorySubcategory
      x-api-path-slug: myfollowscategoriescategorysubcategory-delete
      parameters:
      - in: path
        name: category
      - in: path
        name: subcategory
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Category
      - Subcategory
    get:
      summary: Get My Follows Categories Category Subcategory
      description: Get my follows categories category subcategory.
      operationId: getMyFollowsCategoriesCategorySubcategory
      x-api-path-slug: myfollowscategoriescategorysubcategory-get
      parameters:
      - in: path
        name: category
      - in: path
        name: subcategory
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Category
      - Subcategory
    post:
      summary: Post My Follows Categories Category Subcategory
      description: Post my follows categories category subcategory.
      operationId: postMyFollowsCategoriesCategorySubcategory
      x-api-path-slug: myfollowscategoriescategorysubcategory-post
      parameters:
      - in: path
        name: category
      - in: path
        name: subcategory
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Category
      - Subcategory
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