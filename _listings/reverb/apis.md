---
name: Reverb
x-slug: reverb
description: 'Reverb&#8217;s mission is to connect people with meaningful content.Reverb
  was created to find and connect the rich associations between words, ideas, content,
  and people. Through our products, we enhance broader knowledge around favorite topics
  by surfacing interesting information readers might not uncover on their own. We
  make tools for content understanding at every level from the single word on up.
  Wordnik: Get a full view of any word you???re interested in, with definitions, example
  sentences, related words, tweets from Twitter, pictures from Flickr, and much more.Reverb
  for Publishers: Reverb for Publishers brings relevant content to web audiences and
  surfaces additional content for publishers.Reverb for Developers: Reverb is committed
  to the open-source community and is proudly contributing infrastructure software
  to power applications and enterprises both small and gigantic. Our involvement with
  the Wordnik API, Scalatra, Swagger and Atmosphere is detailed on our site.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Reverb
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/apis.md
specificationVersion: "0.14"
apis:
- name: reverb Get Articles
  x-api-slug: reverb
  description: Get articles.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//articles
  tags: Articles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/articles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/articles-get-openapi.md
- name: reverb Get Categories
  x-api-slug: reverb
  description: List of supported product categories
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//categories
  tags: Categories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/categories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/categories-get-openapi.md
- name: reverb Get Categories Flat
  x-api-slug: reverb
  description: Get categories flat.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//categories/flat
  tags: Categories,Flat
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/categoriesflat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/categoriesflat-get-openapi.md
- name: reverb Get Categories Taxonomy
  x-api-slug: reverb
  description: Full taxonomy tree of categories including middle categories
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//categories/taxonomy
  tags: Categories,Taxonomy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/categoriestaxonomy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/categoriestaxonomy-get-openapi.md
- name: reverb Get Categories Product Type Category
  x-api-slug: reverb
  description: Get categories product type category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//categories/{product_type}/{category}
  tags: Categories,Product,Type,Category
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/categoriesproduct-typecategory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/categoriesproduct-typecategory-get-openapi.md
- name: reverb Get Categories Uu
  x-api-slug: reverb
  description: Get category details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//categories/{uuid}
  tags: Categories,Uuid
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/categoriesuuid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/categoriesuuid-get-openapi.md
- name: reverb Get Comparison Shopping Pages
  x-api-slug: reverb
  description: Returns a set of comparison shopping pages based on the current params
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//comparison_shopping_pages
  tags: Comparison,Shopping,Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/comparison-shopping-pages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/comparison-shopping-pages-get-openapi.md
- name: reverb Get Comparison Shopping Pages Find
  x-api-slug: reverb
  description: Get comparison shopping pages find.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//comparison_shopping_pages/find
  tags: Comparison,Shopping,Pages,Find
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/comparison-shopping-pagesfind-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/comparison-shopping-pagesfind-get-openapi.md
- name: reverb Get Comparison Shopping Pages
  x-api-slug: reverb
  description: Get comparison shopping pages.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//comparison_shopping_pages/{id}
  tags: Comparison,Shopping,Pages,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/comparison-shopping-pagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/comparison-shopping-pagesid-get-openapi.md
- name: reverb Get Comparison Shopping Pages Listings
  x-api-slug: reverb
  description: Return new or used listings for a comparison shopping page
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//comparison_shopping_pages/{id}/listings
  tags: Comparison,Shopping,Pages,Id,Listings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/comparison-shopping-pagesidlistings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/comparison-shopping-pagesidlistings-get-openapi.md
- name: reverb Get Comparison Shopping Pages Reviews
  x-api-slug: reverb
  description: View reviews of a comparison shopping page
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//comparison_shopping_pages/{id}/reviews
  tags: Comparison,Shopping,Pages,Id,Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/comparison-shopping-pagesidreviews-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/comparison-shopping-pagesidreviews-get-openapi.md
- name: reverb Post Conversations Conversation Offer
  x-api-slug: reverb
  description: Make an offer to the other participant in the conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//conversations/{conversation_id}/offer
  tags: Conversations,Conversation,Id,Offer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/conversationsconversation-idoffer-post-openapi.md
- name: reverb Post Conversations Offer
  x-api-slug: reverb
  description: Make an offer to the other participant in the conversation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//conversations/{id}/offer
  tags: Conversations,Id,Offer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/conversationsidoffer-post-openapi.md
- name: reverb Get Countries
  x-api-slug: reverb
  description: Retrieve a list of country codes with corresponding subregions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//countries
  tags: Countries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/countries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/countries-get-openapi.md
- name: reverb Get Csps
  x-api-slug: reverb
  description: Returns a set of comparison shopping pages based on the current params
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//csps
  tags: Csps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/csps-get-openapi.md
- name: reverb Get Csps Categories
  x-api-slug: reverb
  description: Get csps categories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//csps/categories
  tags: Csps,Categories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/cspscategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/cspscategories-get-openapi.md
- name: reverb Get Curated Sets Slug
  x-api-slug: reverb
  description: Get curated sets slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//curated_sets/{slug}
  tags: Curated,Sets,Slug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/curated-setsslug-get-openapi.md
- name: reverb Get Currencies Display
  x-api-slug: reverb
  description: List of supported display currencies for browsing listings
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//currencies/display
  tags: Currencies,Display
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/currenciesdisplay-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/currenciesdisplay-get-openapi.md
- name: reverb Get Currencies Listing
  x-api-slug: reverb
  description: List of supported listing currencies for shops
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//currencies/listing
  tags: Currencies,Listing
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/currencieslisting-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/currencieslisting-get-openapi.md
- name: reverb Get Feedback Feedback
  x-api-slug: reverb
  description: Get feedback feedback.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//feedback/{feedback_id}
  tags: Feedback,Feedback,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/feedbackfeedback-id-get-openapi.md
- name: reverb Get Handpicked Slug
  x-api-slug: reverb
  description: Get results from a handpicked collection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//handpicked/{slug}
  tags: Handpicked,Slug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/handpickedslug-get-openapi.md
- name: reverb Get Listing Conditions
  x-api-slug: reverb
  description: List of supported product conditions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listing_conditions
  tags: Listing,Conditions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listing-conditions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listing-conditions-get-openapi.md
- name: reverb Get Listings
  x-api-slug: reverb
  description: Default search of listings includes only used & handmade. Add a filter
    to view all listings or use the /listings/all endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings
  tags: Listings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listings-get-openapi.md
- name: reverb Post Listings
  x-api-slug: reverb
  description: Create a listing
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings
  tags: Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listings-post-openapi.md
- name: reverb Get Listings All
  x-api-slug: reverb
  description: All listings including used, handmade, and brand new
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/all
  tags: Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingsall-get-openapi.md
- name: reverb Get Listings Facets Seller Location
  x-api-slug: reverb
  description: Get listings facets seller location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/facets/seller_location
  tags: Listings,Facets,Seller,Location
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingsfacetsseller-location-get-openapi.md
- name: reverb Get Listings Negotiation
  x-api-slug: reverb
  description: Returns the latest negotiation for the requesting user given a listing
    id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{id}/negotiation
  tags: Listings,Id,Negotiation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingsidnegotiation-get-openapi.md
- name: reverb Post Listings Offer
  x-api-slug: reverb
  description: Make an offer to the seller of a listing
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{id}/offer
  tags: Listings,Id,Offer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingsidoffer-post-openapi.md
- name: reverb Get Listings Listing Bump
  x-api-slug: reverb
  description: View available bump tiers and stats for a listing
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{listing_id}/bump
  tags: Listings,Listing,Id,Bump
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingslisting-idbump-get-openapi.md
- name: reverb Post Listings Listing Bump Budget Type
  x-api-slug: reverb
  description: Post listings listing bump budget type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{listing_id}/bump/{budget_type}
  tags: Listings,Listing,Id,Bump,Budget,Type
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingslisting-idbumpbudget-type-post-openapi.md
- name: reverb Post Listings Listing Conversations
  x-api-slug: reverb
  description: Post listings listing conversations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{listing_id}/conversations
  tags: Listings,Listing,Id,Conversations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingslisting-idconversations-post-openapi.md
- name: reverb Get Listings Listing Images
  x-api-slug: reverb
  description: View the images associated with a particular listing
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{listing_id}/images
  tags: Listings,Listing,Id,Images
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingslisting-idimages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingslisting-idimages-get-openapi.md
- name: reverb Delete Listings Listing Images Image
  x-api-slug: reverb
  description: Delete listings listing images image.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{listing_id}/images/{image_id}
  tags: Listings,Listing,Id,Images,Image,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingslisting-idimagesimage-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingslisting-idimagesimage-id-delete-openapi.md
- name: reverb Get Listings Listing Product Bundle
  x-api-slug: reverb
  description: Find a product bundle attached to a listing
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{listing_id}/product_bundle
  tags: Listings,Listing,Id,Product,Bundle
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingslisting-idproduct-bundle-get-openapi.md
- name: reverb Get Listings Listing Sales
  x-api-slug: reverb
  description: See all sales that include a listing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{listing_id}/sales
  tags: Listings,Listing,Id,Sales
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingslisting-idsales-get-openapi.md
- name: reverb Delete Listings Slug
  x-api-slug: reverb
  description: Delete a draft listing. Cannot be used on non-drafts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{slug}
  tags: Listings,Slug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingsslug-delete-openapi.md
- name: reverb Get Listings Slug
  x-api-slug: reverb
  description: Get listings slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{slug}
  tags: Listings,Slug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingsslug-get-openapi.md
- name: reverb Put Listings Slug
  x-api-slug: reverb
  description: Put listings slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{slug}
  tags: Listings,Slug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingsslug-put-openapi.md
- name: reverb Get Listings Slug Edit
  x-api-slug: reverb
  description: Get listings slug edit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{slug}/edit
  tags: Listings,Slug,Edit
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingsslugedit-get-openapi.md
- name: reverb Post Listings Slug Flag
  x-api-slug: reverb
  description: Flag a listing for inappropriate content or fraud
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{slug}/flag
  tags: Listings,Slug,Flag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingsslugflag-post-openapi.md
- name: reverb Get Listings Slug Reviews
  x-api-slug: reverb
  description: Get listings slug reviews.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{slug}/reviews
  tags: Listings,Slug,Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingsslugreviews-get-openapi.md
- name: reverb Post Listings Slug Reviews
  x-api-slug: reverb
  description: Create a review for a listing
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{slug}/reviews
  tags: Listings,Slug,Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingsslugreviews-post-openapi.md
- name: reverb Get Listings Slug Similar Listings
  x-api-slug: reverb
  description: Get listings slug similar listings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//listings/{slug}/similar_listings
  tags: Listings,Slug,Similar,Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/listingsslugsimilar-listings-get-openapi.md
- name: reverb Get My Account
  x-api-slug: reverb
  description: Get account details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/account
  tags: My,Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myaccount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myaccount-get-openapi.md
- name: reverb Put My Account
  x-api-slug: reverb
  description: Update account details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/account
  tags: My,Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myaccount-put-openapi.md
- name: reverb Get My Addresses
  x-api-slug: reverb
  description: See all addresses in your address book
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/addresses
  tags: My,Addresses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myaddresses-get-openapi.md
- name: reverb Post My Addresses
  x-api-slug: reverb
  description: Create a new address in your address book
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/addresses
  tags: My,Addresses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myaddresses-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myaddresses-post-openapi.md
- name: reverb Delete My Addresses Address
  x-api-slug: reverb
  description: Delete an existing address in your address book
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/addresses/{address_id}
  tags: My,Addresses,Address,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myaddressesaddress-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myaddressesaddress-id-delete-openapi.md
- name: reverb Put My Addresses Address
  x-api-slug: reverb
  description: Update an existing address in your address book
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/addresses/{address_id}
  tags: My,Addresses,Address,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myaddressesaddress-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myaddressesaddress-id-put-openapi.md
- name: reverb Get My Conversations
  x-api-slug: reverb
  description: Get a list of your conversations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/conversations
  tags: My,Conversations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myconversations-get-openapi.md
- name: reverb Post My Conversations
  x-api-slug: reverb
  description: Post my conversations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/conversations
  tags: My,Conversations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myconversations-post-openapi.md
- name: reverb Post My Conversations Conversation Messages
  x-api-slug: reverb
  description: Post my conversations conversation messages.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/conversations/{conversation_id}/messages
  tags: My,Conversations,Conversation,Id,Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myconversationsconversation-idmessages-post-openapi.md
- name: reverb Get My Conversations
  x-api-slug: reverb
  description: Display conversation details with messages in natural time order (oldest
    to newest)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/conversations/{id}
  tags: My,Conversations,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myconversationsid-get-openapi.md
- name: reverb Put My Conversations
  x-api-slug: reverb
  description: Mark a conversation read/unread
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/conversations/{id}
  tags: My,Conversations,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myconversationsid-put-openapi.md
- name: reverb Get My Counts
  x-api-slug: reverb
  description: Get your actionable status counts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/counts
  tags: My,Counts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mycounts-get-openapi.md
- name: reverb Delete My Curated Set Product Product
  x-api-slug: reverb
  description: Delete my curated set product product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/curated_set/product/{product_id}
  tags: My,Curated,Set,Product,Product,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mycurated-setproductproduct-id-delete-openapi.md
- name: reverb Post My Curated Set Product Product
  x-api-slug: reverb
  description: Post my curated set product product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/curated_set/product/{product_id}
  tags: My,Curated,Set,Product,Product,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mycurated-setproductproduct-id-post-openapi.md
- name: reverb Get My Feed
  x-api-slug: reverb
  description: Get listings from your feed
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/feed
  tags: My,Feed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfeed-get-openapi.md
- name: reverb Get My Feed Customize
  x-api-slug: reverb
  description: get your feed customization options
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/feed/customize
  tags: My,Feed,Customize
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfeedcustomize-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfeedcustomize-get-openapi.md
- name: reverb Get My Feed Gr
  x-api-slug: reverb
  description: Get my feed gr.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/feed/grid
  tags: My,Feed,Grid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfeedgrid-get-openapi.md
- name: reverb Get My Feedback Received
  x-api-slug: reverb
  description: List of received feedback
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/feedback/received
  tags: My,Feedback,Received
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfeedbackreceived-get-openapi.md
- name: reverb Get My Feedback Sent
  x-api-slug: reverb
  description: List of sent feedback
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/feedback/sent
  tags: My,Feedback,Sent
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfeedbacksent-get-openapi.md
- name: reverb Get My Follows
  x-api-slug: reverb
  description: See what the user is following
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows
  tags: My,Follows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollows-get-openapi.md
- name: reverb Get My Follows Articles
  x-api-slug: reverb
  description: Returns a user's ArticleCategoryFollows
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/articles
  tags: My,Follows,Articles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsarticles-get-openapi.md
- name: reverb Post My Follows Articles
  x-api-slug: reverb
  description: Set a user's ArticleCategoryFollows
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/articles
  tags: My,Follows,Articles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsarticles-post-openapi.md
- name: reverb Delete My Follows Brands Slug
  x-api-slug: reverb
  description: Delete my follows brands slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/brands/{slug}
  tags: My,Follows,Brands,Slug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsbrandsslug-delete-openapi.md
- name: reverb Get My Follows Brands Slug
  x-api-slug: reverb
  description: Get my follows brands slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/brands/{slug}
  tags: My,Follows,Brands,Slug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsbrandsslug-get-openapi.md
- name: reverb Post My Follows Brands Slug
  x-api-slug: reverb
  description: Post my follows brands slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/brands/{slug}
  tags: My,Follows,Brands,Slug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsbrandsslug-post-openapi.md
- name: reverb Delete My Follows Categories Category Subcategory
  x-api-slug: reverb
  description: Delete my follows categories category subcategory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/categories/{category}/{subcategory}
  tags: My,Follows,Categories,Category,Subcategory
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscategoriescategorysubcategory-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscategoriescategorysubcategory-delete-openapi.md
- name: reverb Get My Follows Categories Category Subcategory
  x-api-slug: reverb
  description: Get my follows categories category subcategory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/categories/{category}/{subcategory}
  tags: My,Follows,Categories,Category,Subcategory
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscategoriescategorysubcategory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscategoriescategorysubcategory-get-openapi.md
- name: reverb Post My Follows Categories Category Subcategory
  x-api-slug: reverb
  description: Post my follows categories category subcategory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/categories/{category}/{subcategory}
  tags: My,Follows,Categories,Category,Subcategory
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscategoriescategorysubcategory-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscategoriescategorysubcategory-post-openapi.md
- name: reverb Delete My Follows Categories Entifier
  x-api-slug: reverb
  description: Delete my follows categories entifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/categories/{identifier}
  tags: My,Follows,Categories,Identifier
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscategoriesidentifier-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscategoriesidentifier-delete-openapi.md
- name: reverb Get My Follows Categories Entifier
  x-api-slug: reverb
  description: Get my follows categories entifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/categories/{identifier}
  tags: My,Follows,Categories,Identifier
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscategoriesidentifier-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscategoriesidentifier-get-openapi.md
- name: reverb Post My Follows Categories Entifier
  x-api-slug: reverb
  description: Post my follows categories entifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/categories/{identifier}
  tags: My,Follows,Categories,Identifier
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscategoriesidentifier-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscategoriesidentifier-post-openapi.md
- name: reverb Delete My Follows Collections Slug
  x-api-slug: reverb
  description: Delete my follows collections slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/collections/{slug}
  tags: My,Follows,Collections,Slug
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscollectionsslug-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscollectionsslug-delete-openapi.md
- name: reverb Get My Follows Collections Slug
  x-api-slug: reverb
  description: Get my follows collections slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/collections/{slug}
  tags: My,Follows,Collections,Slug
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscollectionsslug-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscollectionsslug-get-openapi.md
- name: reverb Post My Follows Collections Slug
  x-api-slug: reverb
  description: Post my follows collections slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/collections/{slug}
  tags: My,Follows,Collections,Slug
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscollectionsslug-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowscollectionsslug-post-openapi.md
- name: reverb Delete My Follows Handpicked Slug
  x-api-slug: reverb
  description: Delete my follows handpicked slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/handpicked/{slug}
  tags: My,Follows,Handpicked,Slug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowshandpickedslug-delete-openapi.md
- name: reverb Get My Follows Handpicked Slug
  x-api-slug: reverb
  description: Follow status for a handpicked collection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/handpicked/{slug}
  tags: My,Follows,Handpicked,Slug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowshandpickedslug-get-openapi.md
- name: reverb Post My Follows Handpicked Slug
  x-api-slug: reverb
  description: Post my follows handpicked slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/handpicked/{slug}
  tags: My,Follows,Handpicked,Slug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowshandpickedslug-post-openapi.md
- name: reverb Get My Follows Search
  x-api-slug: reverb
  description: Follow status for a search
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/search
  tags: My,Follows,Search
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowssearch-get-openapi.md
- name: reverb Post My Follows Search
  x-api-slug: reverb
  description: Post my follows search.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/search
  tags: My,Follows,Search
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowssearch-post-openapi.md
- name: reverb Delete My Follows Shops Slug
  x-api-slug: reverb
  description: Delete my follows shops slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/shops/{slug}
  tags: My,Follows,Shops,Slug
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsshopsslug-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsshopsslug-delete-openapi.md
- name: reverb Get My Follows Shops Slug
  x-api-slug: reverb
  description: Get my follows shops slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/shops/{slug}
  tags: My,Follows,Shops,Slug
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsshopsslug-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsshopsslug-get-openapi.md
- name: reverb Post My Follows Shops Slug
  x-api-slug: reverb
  description: Post my follows shops slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/shops/{slug}
  tags: My,Follows,Shops,Slug
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsshopsslug-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsshopsslug-post-openapi.md
- name: reverb Delete My Follows Follow
  x-api-slug: reverb
  description: Delete my follows follow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/{follow_id}
  tags: My,Follows,Follow,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsfollow-id-delete-openapi.md
- name: reverb Delete My Follows Follow Alert
  x-api-slug: reverb
  description: Delete my follows follow alert.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/{follow_id}/alert
  tags: My,Follows,Follow,Id,Alert
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsfollow-idalert-delete-openapi.md
- name: reverb Post My Follows Follow Alert
  x-api-slug: reverb
  description: Post my follows follow alert.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/follows/{follow_id}/alert
  tags: My,Follows,Follow,Id,Alert
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myfollowsfollow-idalert-post-openapi.md
- name: reverb Get My Listings
  x-api-slug: reverb
  description: Retrieve a list of live listings for the seller. To search all listings
    specify state=all
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/listings
  tags: My,Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mylistings-get-openapi.md
- name: reverb Get My Listings Drafts
  x-api-slug: reverb
  description: Retrieve a list your draft listings
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/listings/drafts
  tags: My,Listings,Drafts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mylistingsdrafts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mylistingsdrafts-get-openapi.md
- name: reverb Get My Listings Negotiations
  x-api-slug: reverb
  description: Get a list of active negotiations as a seller
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/listings/negotiations
  tags: My,Listings,Negotiations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mylistingsnegotiations-get-openapi.md
- name: reverb Put My Listings Slug State End
  x-api-slug: reverb
  description: Put my listings slug state end.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/listings/{slug}/state/end
  tags: My,Listings,Slug,State,End
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mylistingsslugstateend-put-openapi.md
- name: reverb Get My Lists
  x-api-slug: reverb
  description: Get a list of your lists (wishlist, watch list, etc)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/lists
  tags: My,Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mylists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mylists-get-openapi.md
- name: reverb Get My Negotiations Buying
  x-api-slug: reverb
  description: Get a list of active negotiations as a buyer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/negotiations/buying
  tags: My,Negotiations,Buying
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mynegotiationsbuying-get-openapi.md
- name: reverb Get My Negotiations
  x-api-slug: reverb
  description: Get my negotiations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/negotiations/{id}
  tags: My,Negotiations,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mynegotiationsid-get-openapi.md
- name: reverb Post My Negotiations Accept
  x-api-slug: reverb
  description: Post my negotiations accept.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/negotiations/{id}/accept
  tags: My,Negotiations,Id,Accept
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mynegotiationsidaccept-post-openapi.md
- name: reverb Post My Negotiations Counter
  x-api-slug: reverb
  description: Post my negotiations counter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/negotiations/{id}/counter
  tags: My,Negotiations,Id,Counter
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mynegotiationsidcounter-post-openapi.md
- name: reverb Post My Negotiations Decline
  x-api-slug: reverb
  description: Post my negotiations decline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/negotiations/{id}/decline
  tags: My,Negotiations,Id,Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mynegotiationsiddecline-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mynegotiationsiddecline-post-openapi.md
- name: reverb Get My Orders Awaiting Feedback
  x-api-slug: reverb
  description: List of orders that need feedback
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/awaiting_feedback
  tags: My,Orders,Awaiting,Feedback
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myordersawaiting-feedback-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myordersawaiting-feedback-get-openapi.md
- name: reverb Get My Orders Buying All
  x-api-slug: reverb
  description: Returns all orders, newest first.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/buying/all
  tags: My,Orders,Buying
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myordersbuyingall-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myordersbuyingall-get-openapi.md
- name: reverb Get My Orders Buying Unpa
  x-api-slug: reverb
  description: Returns unpaid orders, newest first.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/buying/unpaid
  tags: My,Orders,Buying,Unpaid
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myordersbuyingunpaid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myordersbuyingunpaid-get-openapi.md
- name: reverb Get My Orders Buying
  x-api-slug: reverb
  description: Returns order details for a buyer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/buying/{id}
  tags: My,Orders,Buying,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myordersbuyingid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myordersbuyingid-get-openapi.md
- name: reverb Post My Orders Buying Mark Received
  x-api-slug: reverb
  description: Marks an order as received by the buyer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/buying/{id}/mark_received
  tags: My,Orders,Buying,Id,Mark,Received
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myordersbuyingidmark-received-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myordersbuyingidmark-received-post-openapi.md
- name: reverb Get My Orders Selling All
  x-api-slug: reverb
  description: Get all seller orders, newest first.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/selling/all
  tags: My,Orders,Selling
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myorderssellingall-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myorderssellingall-get-openapi.md
- name: reverb Get My Orders Selling Awaiting Shipment
  x-api-slug: reverb
  description: Get seller orders awaiting shipment, newest first.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/selling/awaiting_shipment
  tags: My,Orders,Selling,Awaiting,Shipment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myorderssellingawaiting-shipment-get-openapi.md
- name: reverb Get My Orders Selling Buyer History Buyer
  x-api-slug: reverb
  description: Get my orders selling buyer history buyer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/selling/buyer_history/{buyer_id}
  tags: My,Orders,Selling,Buyer,History,Buyer,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myorderssellingbuyer-historybuyer-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myorderssellingbuyer-historybuyer-id-get-openapi.md
- name: reverb Get My Orders Selling Unpa
  x-api-slug: reverb
  description: Get unpaid seller orders, newest first.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/selling/unpaid
  tags: My,Orders,Selling,Unpaid
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myorderssellingunpaid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myorderssellingunpaid-get-openapi.md
- name: reverb Get My Orders Selling
  x-api-slug: reverb
  description: Returns order details for a seller
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/selling/{id}
  tags: My,Orders,Selling,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myorderssellingid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myorderssellingid-get-openapi.md
- name: reverb Post My Orders Selling Mark Picked Up
  x-api-slug: reverb
  description: Post my orders selling mark picked up.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/selling/{id}/mark_picked_up
  tags: My,Orders,Selling,Id,Mark,Picked,Up
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myorderssellingidmark-picked-up-post-openapi.md
- name: reverb Post My Orders Selling Ship
  x-api-slug: reverb
  description: Post my orders selling ship.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/selling/{id}/ship
  tags: My,Orders,Selling,Id,Ship
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myorderssellingidship-post-openapi.md
- name: reverb Post My Orders Selling Order Refund Requests
  x-api-slug: reverb
  description: Post my orders selling order refund requests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/selling/{order_id}/refund_requests
  tags: My,Orders,Selling,Order,Id,Refund,Requests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myorderssellingorder-idrefund-requests-post-openapi.md
- name: reverb Get My Payments Selling
  x-api-slug: reverb
  description: Get my payments selling.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/payments/selling
  tags: My,Payments,Selling
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mypaymentsselling-get-openapi.md
- name: reverb Get My Payments Selling
  x-api-slug: reverb
  description: Get my payments selling.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/payments/selling/{id}
  tags: My,Payments,Selling,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mypaymentssellingid-get-openapi.md
- name: reverb Get My Payouts
  x-api-slug: reverb
  description: Get a list of payouts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/payouts
  tags: My,Payouts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mypayouts-get-openapi.md
- name: reverb Get My Payouts Line Items
  x-api-slug: reverb
  description: Read the line items of a payout
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/payouts/{id}/line_items
  tags: My,Payouts,Id,Line,Items
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mypayoutsidline-items-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mypayoutsidline-items-get-openapi.md
- name: reverb Get My Refund Requests Selling
  x-api-slug: reverb
  description: Get a list of refund requests as a seller
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/refund_requests/selling
  tags: My,Refund,Requests,Selling
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myrefund-requestsselling-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myrefund-requestsselling-get-openapi.md
- name: reverb Put My Refund Requests Selling
  x-api-slug: reverb
  description: Update a refund request for a sold order
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/refund_requests/selling/{id}
  tags: My,Refund,Requests,Selling,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myrefund-requestssellingid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myrefund-requestssellingid-put-openapi.md
- name: reverb Get My Viewed Listings
  x-api-slug: reverb
  description: Get a list of your recently viewed listings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/viewed_listings
  tags: My,Viewed,Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myviewed-listings-get-openapi.md
- name: reverb Get My Wishlist
  x-api-slug: reverb
  description: Get a list of wishlisted items
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/wishlist
  tags: My,Wishlist
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mywishlist-get-openapi.md
- name: reverb Delete My Wishlist
  x-api-slug: reverb
  description: Remove a listing from your wishlist
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/wishlist/{id}
  tags: My,Wishlist,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mywishlistid-delete-openapi.md
- name: reverb Put My Wishlist
  x-api-slug: reverb
  description: Add a listing to your wishlist
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/wishlist/{id}
  tags: My,Wishlist,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/mywishlistid-put-openapi.md
- name: reverb Get Orders Order Feedback Buyer
  x-api-slug: reverb
  description: Feedback details for an order's buyer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//orders/{order_id}/feedback/buyer
  tags: Orders,Order,Id,Feedback,Buyer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/ordersorder-idfeedbackbuyer-get-openapi.md
- name: reverb Post Orders Order Feedback Buyer
  x-api-slug: reverb
  description: Add feedback about an order's buyer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//orders/{order_id}/feedback/buyer
  tags: Orders,Order,Id,Feedback,Buyer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/ordersorder-idfeedbackbuyer-post-openapi.md
- name: reverb Get Orders Order Feedback Seller
  x-api-slug: reverb
  description: Feedback details for an order's seller
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//orders/{order_id}/feedback/seller
  tags: Orders,Order,Id,Feedback,Seller
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/ordersorder-idfeedbackseller-get-openapi.md
- name: reverb Post Orders Order Feedback Seller
  x-api-slug: reverb
  description: Add feedback about an order's seller
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//orders/{order_id}/feedback/seller
  tags: Orders,Order,Id,Feedback,Seller
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/ordersorder-idfeedbackseller-post-openapi.md
- name: reverb Get Payment Methods
  x-api-slug: reverb
  description: Get list of payment methods
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//payment_methods
  tags: Payment,Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/payment-methods-get-openapi.md
- name: reverb Get Pricegue
  x-api-slug: reverb
  description: Search the Price Guide
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//priceguide
  tags: Priceguide
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/priceguide-get-openapi.md
- name: reverb Get Pricegue
  x-api-slug: reverb
  description: Retrieve a Price Guide
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//priceguide/{id}
  tags: Priceguide,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/priceguideid-get-openapi.md
- name: reverb Get Pricegue Transactions
  x-api-slug: reverb
  description: Get a list of paginated transactions for a price guide.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//priceguide/{id}/transactions
  tags: Priceguide,Id,Transactions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/priceguideidtransactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/priceguideidtransactions-get-openapi.md
- name: reverb Get Pricegue Transactions Summary
  x-api-slug: reverb
  description: Get a summary of transactions for a given price guide
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//priceguide/{id}/transactions/summary
  tags: Priceguide,Id,Transactions,Summary
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/priceguideidtransactionssummary-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/priceguideidtransactionssummary-get-openapi.md
- name: reverb Get Products Reviews
  x-api-slug: reverb
  description: Get products reviews.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//products/reviews/{id}
  tags: Products,Reviews,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/productsreviewsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/productsreviewsid-get-openapi.md
- name: reverb Put Products Reviews
  x-api-slug: reverb
  description: Put products reviews.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//products/reviews/{id}
  tags: Products,Reviews,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/productsreviewsid-put-openapi.md
- name: reverb Get Products Slug Reviews
  x-api-slug: reverb
  description: View reviews of a comparison shopping page
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//products/{slug}/reviews
  tags: Products,Slug,Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/productsslugreviews-get-openapi.md
- name: reverb Post Products Slug Reviews
  x-api-slug: reverb
  description: Create a review for a product
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//products/{slug}/reviews
  tags: Products,Slug,Reviews
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/productsslugreviews-post-openapi.md
- name: reverb Get Sales Reverb
  x-api-slug: reverb
  description: View upcoming and live Reverb official sales.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//sales/reverb
  tags: Sales,Reverb
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/salesreverb-get-openapi.md
- name: reverb Get Sales Seller
  x-api-slug: reverb
  description: View your created sales.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//sales/seller
  tags: Sales,Seller
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/salesseller-get-openapi.md
- name: reverb Delete Sales Sale Listings
  x-api-slug: reverb
  description: Remove a listing from a sale
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//sales/{sale_id}/listings
  tags: Sales,Sale,Id,Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/salessale-idlistings-delete-openapi.md
- name: reverb Post Sales Sale Listings
  x-api-slug: reverb
  description: Post sales sale listings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//sales/{sale_id}/listings
  tags: Sales,Sale,Id,Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/salessale-idlistings-post-openapi.md
- name: reverb Get Sales Slug
  x-api-slug: reverb
  description: Get sales slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//sales/{slug}
  tags: Sales,Slug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/salesslug-get-openapi.md
- name: reverb Get Shipping Provers
  x-api-slug: reverb
  description: List of supported shipping providers
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shipping/providers
  tags: Shipping,Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shippingproviders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shippingproviders-get-openapi.md
- name: reverb Get Shipping Regions
  x-api-slug: reverb
  description: Get shipping regions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shipping/regions
  tags: Shipping,Regions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shippingregions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shippingregions-get-openapi.md
- name: reverb Get Shop
  x-api-slug: reverb
  description: Get your own shop details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shop
  tags: Shop
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shop-get-openapi.md
- name: reverb Put Shop
  x-api-slug: reverb
  description: Update your shop profile
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shop
  tags: Shop
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shop-put-openapi.md
- name: reverb Get Shop Listing Conditions
  x-api-slug: reverb
  description: List of supported product conditions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shop/listing_conditions
  tags: Shop,Listing,Conditions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shoplisting-conditions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shoplisting-conditions-get-openapi.md
- name: reverb Get Shop Payment Methods
  x-api-slug: reverb
  description: Get accepted payment methods
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shop/payment_methods
  tags: Shop,Payment,Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shoppayment-methods-get-openapi.md
- name: reverb Delete Shop Vacation
  x-api-slug: reverb
  description: Disable vacation mode. All listings will be re-enabled.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shop/vacation
  tags: Shop,Vacation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopvacation-delete-openapi.md
- name: reverb Get Shop Vacation
  x-api-slug: reverb
  description: Returns shop vacation status
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shop/vacation
  tags: Shop,Vacation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopvacation-get-openapi.md
- name: reverb Post Shop Vacation
  x-api-slug: reverb
  description: Enable vacation mode. All listings will be unavailable until vacation
    mode is turned off.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shop/vacation
  tags: Shop,Vacation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopvacation-post-openapi.md
- name: reverb Get Shops Storefronts
  x-api-slug: reverb
  description: Get storefront details on a shop.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shops/{id}/storefronts
  tags: Shops,Id,Storefronts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopsidstorefronts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopsidstorefronts-get-openapi.md
- name: reverb Get Shops Shop Shipping Profiles
  x-api-slug: reverb
  description: List of shipping profiles for your shop
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shops/{shop_id}/shipping_profiles
  tags: Shops,Shop,Id,Shipping,Profiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopsshop-idshipping-profiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopsshop-idshipping-profiles-get-openapi.md
- name: reverb Get Shops Slug
  x-api-slug: reverb
  description: Get details on a shop.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shops/{slug}
  tags: Shops,Slug
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopsslug-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopsslug-get-openapi.md
- name: reverb Get Shops Slug Feedback
  x-api-slug: reverb
  description: Get shops slug feedback.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shops/{slug}/feedback
  tags: Shops,Slug,Feedback
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopsslugfeedback-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopsslugfeedback-get-openapi.md
- name: reverb Get Shops Slug Feedback Buyer
  x-api-slug: reverb
  description: Get seller's feedback as a buyer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shops/{slug}/feedback/buyer
  tags: Shops,Slug,Feedback,Buyer
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopsslugfeedbackbuyer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopsslugfeedbackbuyer-get-openapi.md
- name: reverb Get Shops Slug Feedback Seller
  x-api-slug: reverb
  description: Get seller's feedback as a seller
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shops/{slug}/feedback/seller
  tags: Shops,Slug,Feedback,Seller
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopsslugfeedbackseller-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopsslugfeedbackseller-get-openapi.md
- name: reverb Get Wants
  x-api-slug: reverb
  description: A list of wanted items by the user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//wants
  tags: Wants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/wants-get-openapi.md
- name: reverb Delete Wants
  x-api-slug: reverb
  description: Unmark an item wanted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//wants/{id}
  tags: Wants,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/wantsid-delete-openapi.md
- name: reverb Put Wants
  x-api-slug: reverb
  description: Mark an item wanted. Returns 200 on success or 422 on failure.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//wants/{id}
  tags: Wants,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/wantsid-put-openapi.md
- name: reverb Get Webhooks Registrations
  x-api-slug: reverb
  description: Get webhooks registrations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//webhooks/registrations
  tags: Webhooks,Registrations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/webhooksregistrations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/webhooksregistrations-get-openapi.md
- name: reverb Post Webhooks Registrations
  x-api-slug: reverb
  description: Post webhooks registrations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//webhooks/registrations
  tags: Webhooks,Registrations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/webhooksregistrations-post-openapi.md
- name: reverb Delete Webhooks Registrations
  x-api-slug: reverb
  description: Delete webhooks registrations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//webhooks/registrations/{id}
  tags: Webhooks,Registrations,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/webhooksregistrationsid-delete-openapi.md
- name: reverb Get Webhooks Registrations
  x-api-slug: reverb
  description: Get details of a webhook registration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//webhooks/registrations/{id}
  tags: Webhooks,Registrations,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/webhooksregistrationsid-get-openapi.md
- name: reverb Post Accounts
  x-api-slug: reverb
  description: Create an account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//accounts
  tags: Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/accounts-post-openapi.md
- name: reverb Get Articles Featured
  x-api-slug: reverb
  description: See featured Reverb blog posts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//articles/featured
  tags: Articles,Featured
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/articlesfeatured-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/articlesfeatured-get-openapi.md
- name: reverb Get Articles Recently Featured
  x-api-slug: reverb
  description: Get articles recently featured.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//articles/recently_featured
  tags: Articles,Recently,Featured
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/articlesrecently-featured-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/articlesrecently-featured-get-openapi.md
- name: reverb Get Articles Slug
  x-api-slug: reverb
  description: Display a single article
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//articles/{slug}
  tags: Articles,Slug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/articlesslug-get-openapi.md
- name: reverb Get Articles Slug Related Listings
  x-api-slug: reverb
  description: Find listings related to an article
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//articles/{slug}/related-listings
  tags: Articles,Slug,Related-listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/articlesslugrelatedlistings-get-openapi.md
- name: reverb Post Auth Forgot Password
  x-api-slug: reverb
  description: Send a password reset email
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//auth/forgot_password
  tags: Auth,Forgot,Password
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/authforgot-password-post-openapi.md
- name: reverb Put Auth Logout
  x-api-slug: reverb
  description: Logout (primarily for mobile clients)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//auth/logout
  tags: Auth,Logout
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/authlogout-put-openapi.md
- name: reverb Get Autosuggest
  x-api-slug: reverb
  description: Autosuggest terms for searches
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//autosuggest
  tags: Autosuggest
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/autosuggest-get-openapi.md
- name: reverb Get Cart
  x-api-slug: reverb
  description: Get all cart items
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//cart
  tags: Cart
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/cart-get-openapi.md
- name: reverb Post Cart Move To Watch List Cart Item
  x-api-slug: reverb
  description: Remove a cart item and add it to watch list
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//cart/move_to_watch_list/{cart_item_id}
  tags: Cart,Move,To,Watch,List,Cart,Item,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/cartmove-to-watch-listcart-item-id-post-openapi.md
- name: reverb Delete Cart
  x-api-slug: reverb
  description: Remove a product from the cart
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//cart/{id}
  tags: Cart,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/cartid-delete-openapi.md
- name: reverb Post Cart
  x-api-slug: reverb
  description: Add product to the cart
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//cart/{id}
  tags: Cart,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/cartid-post-openapi.md
- name: reverb Put Cart
  x-api-slug: reverb
  description: Update cart item details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//cart/{id}
  tags: Cart,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/cartid-put-openapi.md
- name: reverb Get Collections
  x-api-slug: reverb
  description: List of curated collections
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//collections
  tags: Collections
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/collections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/collections-get-openapi.md
- name: reverb Get Collections Slug
  x-api-slug: reverb
  description: Get collections slug.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//collections/{slug}
  tags: Collections,Slug
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/collectionsslug-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/collectionsslug-get-openapi.md
- name: reverb Get My Orders Buying Buying History Seller
  x-api-slug: reverb
  description: Get my orders buying buying history seller.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//my/orders/buying/buying_history/{seller_id}
  tags: My,Orders,Buying,Buying,History,Seller,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myordersbuyingbuying-historyseller-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/myordersbuyingbuying-historyseller-id-get-openapi.md
- name: reverb Get Shop Stats
  x-api-slug: reverb
  description: Get listings stats
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shop/stats
  tags: Shop,Stats
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopstats-get-openapi.md
- name: reverb Get Shop Stats Activity
  x-api-slug: reverb
  description: Get shop activity for a particular time period
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//shop/stats/activity
  tags: Shop,Stats,Activity
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/shopstatsactivity-get-openapi.md
- name: reverb Get Vinyl Listings
  x-api-slug: reverb
  description: Get vinyl listings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//vinyl/listings
  tags: Vinyl,Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/vinyllistings-get-openapi.md
- name: reverb Post Vinyl Listings
  x-api-slug: reverb
  description: Post vinyl listings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//vinyl/listings
  tags: Vinyl,Listings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/vinyllistings-post-openapi.md
- name: reverb Get Vinyl Listings
  x-api-slug: reverb
  description: Get vinyl listings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//vinyl/listings/{id}
  tags: Vinyl,Listings,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/vinyllistingsid-get-openapi.md
- name: reverb
  x-api-slug: reverb
  description: 'Reverb&#8217;s mission is to connect people with meaningful content.Reverb
    was created to find and connect the rich associations between words, ideas, content,
    and people. Through our products, we enhance broader knowledge around favorite
    topics by surfacing interesting information readers might not uncover on their
    own. We make tools for content understanding at every level from the single word
    on up. Wordnik: Get a full view of any word you???re interested in, with definitions,
    example sentences, related words, tweets from Twitter, pictures from Flickr, and
    much more.Reverb for Publishers: Reverb for Publishers brings relevant content
    to web audiences and surfaces additional content for publishers.Reverb for Developers:
    Reverb is committed to the open-source community and is proudly contributing infrastructure
    software to power applications and enterprises both small and gigantic. Our involvement
    with the Wordnik API, Scalatra, Swagger and Atmosphere is detailed on our site.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api
  tags: Reverb
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reverb/master/_listings/reverb/openapi.md
x-common:
- type: x-blog
  url: http://blog.helloreverb.com/
- type: x-blog-rss
  url: http://blog.helloreverb.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/reverb-technologies
- type: x-github
  url: https://github.com/reverb
- type: x-twitter
  url: https://twitter.com/reverb
- type: x-website
  url: https://helloreverb.com/app
- type: x-website
  url: http://reverb.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---