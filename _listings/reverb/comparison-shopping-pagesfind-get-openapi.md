---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: Reverb Get Comparison Shopping Pages Find
  description: Get comparison shopping pages find.
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