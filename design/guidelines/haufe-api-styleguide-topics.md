---
layout: guideline
title: Haufe API style guide
permalink: /design/guidelines/haufe-api-styleguide
data:
  items:
    - references:
        - name: Filtering
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#filtering'
        - name: Time selection
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#time-selection'
        - name: Search
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/search/search.md'
      _embedded:
        topic:
          id: collection-filtering
          name: Filtering
          description: How to select some resources in a collection
          _links:
            self:
              href: /design/topics/collection-filtering
            topicGuidelines:
              href: /design/topics/collection-filtering/guidelines
      _links:
        topic:
          href: /design/topics/collection-filtering
    - references:
        - name: Paging
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#paging'
      _embedded:
        topic:
          id: collection-pagination
          name: Pagination
          description: How to retrieve a range of resources in a collection
          _links:
            self:
              href: /design/topics/collection-pagination
            topicGuidelines:
              href: /design/topics/collection-pagination/guidelines
      _links:
        topic:
          href: /design/topics/collection-pagination
    - references:
        - name: Get List of resources
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#get-list-of-resources'
      _embedded:
        topic:
          id: collection-retrieve
          name: Retrieve a collection
          description: How to get a collection or resources
          _links:
            self:
              href: /design/topics/collection-retrieve
            topicGuidelines:
              href: /design/topics/collection-retrieve/guidelines
      _links:
        topic:
          href: /design/topics/collection-retrieve
    - references:
        - name: Sorting
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#sorting'
      _embedded:
        topic:
          id: collection-sorting
          name: Sorting a collection
          description: How to sort a collection of resources
          _links:
            self:
              href: /design/topics/collection-sorting
            topicGuidelines:
              href: /design/topics/collection-sorting/guidelines
      _links:
        topic:
          href: /design/topics/collection-sorting
    - references:
        - name: Collection Resources
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md'
      _embedded:
        topic:
          id: collection
          name: Collection
          description: What is a collection (set) of resources
          _links:
            self:
              href: /design/topics/collection
            topicGuidelines:
              href: /design/topics/collection/guidelines
      _links:
        topic:
          href: /design/topics/collection
    - references:
        - name: Currency
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/type-formatting/type-formatting.md#currency'
          quote: 3-character ISO-4217
        - name: Country
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/type-formatting/type-formatting.md#country'
          quote: ISO 3166-1-alpha-2
      _embedded:
        topic:
          id: data-standards
          name: Standards data
          description: 'Which standard use for values like languages, countries, currencies, ...'
          _links:
            self:
              href: /design/topics/data-standards
            topicGuidelines:
              href: /design/topics/data-standards/guidelines
      _links:
        topic:
          href: /design/topics/data-standards
    - references:
        - name: Dates and Times
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/type-formatting/type-formatting.md#dates-and-times'
      _embedded:
        topic:
          id: data-format-date-time
          name: Date and Time
          description: How to deal with date and time data
          _links:
            self:
              href: /design/topics/data-format-date-time
            topicGuidelines:
              href: /design/topics/data-format-date-time/guidelines
      _links:
        topic:
          href: /design/topics/data-format-date-time
    - references:
        - name: Hypermedia Response Format
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/response-format/response-format.md'
        - name: Type Formatting
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/type-formatting/type-formatting.md'
        - name: Message Schema and Postel's Law
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/message-schema/message-schema.md'
      _embedded:
        topic:
          id: data-format
          name: Data format
          description: which data format use
          _links:
            self:
              href: /design/topics/data-format
            topicGuidelines:
              href: /design/topics/data-format/guidelines
      _links:
        topic:
          href: /design/topics/data-format
    - references:
        - name: Documentation
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/documentation/documentation.md'
      _embedded:
        topic:
          id: developer-experience
          name: Developer experience
          description: How to take care of developer experience (DX)
          _links:
            self:
              href: /design/topics/developer-experience
            topicGuidelines:
              href: /design/topics/developer-experience/guidelines
      _links:
        topic:
          href: /design/topics/developer-experience
    - references:
        - name: Every API MUST be described using a formal API description language
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/general-guidelines/general-guidelines.md#every-api-must-be-described-using-a-formal-api-description-language'
        - name: Documentation
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/documentation/documentation.md'
      _embedded:
        topic:
          id: documentation
          name: Documentation
          description: How to produce and/or propose API documentation
          _links:
            self:
              href: /design/topics/documentation
            topicGuidelines:
              href: /design/topics/documentation/guidelines
      _links:
        topic:
          href: /design/topics/documentation
    - references:
        - name: Error handling
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/error-handling/error-handling.md'
      _embedded:
        topic:
          id: errors
          name: Errors
          description: How to handle errors
          _links:
            self:
              href: /design/topics/errors
            topicGuidelines:
              href: /design/topics/errors/guidelines
      _links:
        topic:
          href: /design/topics/errors
    - references:
        - name: Introduction
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/introduction/introduction.md'
        - name: General Guidelines
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/general-guidelines/general-guidelines.md'
        - name: Message Schema and Postel's Law
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/message-schema/message-schema.md'
      _embedded:
        topic:
          id: global-design
          name: Global design
          description: General considerations on API design
          _links:
            self:
              href: /design/topics/global-design
            topicGuidelines:
              href: /design/topics/global-design/guidelines
      _links:
        topic:
          href: /design/topics/global-design
    - references:
        - name: API Modelling and Design Process
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#api-modelling-and-design-process'
        - name: API Design Review Process
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-review-process/api-design-review-process.md'
        - name: Message Schema and Postel's Law
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/message-schema/message-schema.md'
      _embedded:
        topic:
          id: governance
          name: Governance
          description: 'How to ensure API governance (advertise, consistency, ...)'
          _links:
            self:
              href: /design/topics/governance
            topicGuidelines:
              href: /design/topics/governance/guidelines
      _links:
        topic:
          href: /design/topics/governance
    - references:
        - name: Caching
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md'
      _embedded:
        topic:
          id: http-caching
          name: Caching
          description: How to use and provide relevant caching informations
          _links:
            self:
              href: /design/topics/http-caching
            topicGuidelines:
              href: /design/topics/http-caching/guidelines
      _links:
        topic:
          href: /design/topics/http-caching
    - references:
        - name: Expires HTTP Header
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#expires-http-header'
        - name: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#cache-control-header'
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#cache-control-header'
        - name: ETag
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#etag'
      _embedded:
        topic:
          id: http-headers
          name: HTTP Headers
          description: How to use standard or custom HTTP headers
          _links:
            self:
              href: /design/topics/http-headers
            topicGuidelines:
              href: /design/topics/http-headers/guidelines
      _links:
        topic:
          href: /design/topics/http-headers
    - references:
        - name: HTTP Status (Get List of resources)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status'
        - name: HTTP Status (Read Single Resource)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-1'
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-200
          name: HTTP Status 200
          description: When to use HTTP status 200
          _links:
            self:
              href: /design/topics/http-status-200
            topicGuidelines:
              href: /design/topics/http-status-200/guidelines
      _links:
        topic:
          href: /design/topics/http-status-200
    - references:
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-201
          name: HTTP Status 201
          description: When to use HTTP status 201
          _links:
            self:
              href: /design/topics/http-status-201
            topicGuidelines:
              href: /design/topics/http-status-201/guidelines
      _links:
        topic:
          href: /design/topics/http-status-201
    - references:
        - name: HTTP Status (Update Single Resource)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-2'
        - name: HTTP Status (Update Partial Single Resource)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-3'
        - name: Delete Single Resource
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#delete-single-resource'
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-204
          name: HTTP Status 204
          description: When to use HTTP status 204
          _links:
            self:
              href: /design/topics/http-status-204
            topicGuidelines:
              href: /design/topics/http-status-204/guidelines
      _links:
        topic:
          href: /design/topics/http-status-204
    - references:
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-304
          name: HTTP Status 304
          description: When to use HTTP status 304
          _links:
            self:
              href: /design/topics/http-status-304
            topicGuidelines:
              href: /design/topics/http-status-304/guidelines
      _links:
        topic:
          href: /design/topics/http-status-304
    - references:
        - name: HTTP Status (Get List of resources)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status'
        - name: HTTP Status (Update Single Resource)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-2'
        - name: HTTP Status (Update Partial Single Resource)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-3'
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-400
          name: HTTP Status 400
          description: When to use HTTP status 400
          _links:
            self:
              href: /design/topics/http-status-400
            topicGuidelines:
              href: /design/topics/http-status-400/guidelines
      _links:
        topic:
          href: /design/topics/http-status-400
    - references:
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-401
          name: HTTP Status 401
          description: When to use HTTP status 401
          _links:
            self:
              href: /design/topics/http-status-401
            topicGuidelines:
              href: /design/topics/http-status-401/guidelines
      _links:
        topic:
          href: /design/topics/http-status-401
    - references:
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-403
          name: HTTP Status 403
          description: When to use HTTP status 403
          _links:
            self:
              href: /design/topics/http-status-403
            topicGuidelines:
              href: /design/topics/http-status-403/guidelines
      _links:
        topic:
          href: /design/topics/http-status-403
    - references:
        - name: HTTP Status (Get List of resources)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status'
        - name: HTTP Status (Read Single Resource)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-1'
        - name: Delete Single Resource
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#delete-single-resource'
          quote: 404 Not Found HTTP status should not be utilized
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-404
          name: HTTP Status 404
          description: When to use HTTP status 404
          _links:
            self:
              href: /design/topics/http-status-404
            topicGuidelines:
              href: /design/topics/http-status-404/guidelines
      _links:
        topic:
          href: /design/topics/http-status-404
    - references:
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-405
          name: HTTP Status 405
          description: When to use HTTP status 405
          _links:
            self:
              href: /design/topics/http-status-405
            topicGuidelines:
              href: /design/topics/http-status-405/guidelines
      _links:
        topic:
          href: /design/topics/http-status-405
    - references:
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-406
          name: HTTP Status 406
          description: When to use HTTP status 406
          _links:
            self:
              href: /design/topics/http-status-406
            topicGuidelines:
              href: /design/topics/http-status-406/guidelines
      _links:
        topic:
          href: /design/topics/http-status-406
    - references:
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-408
          name: HTTP Status 408
          description: When to use HTTP status 408
          _links:
            self:
              href: /design/topics/http-status-408
            topicGuidelines:
              href: /design/topics/http-status-408/guidelines
      _links:
        topic:
          href: /design/topics/http-status-408
    - references:
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-409
          name: HTTP Status 409
          description: When to use HTTP status 409
          _links:
            self:
              href: /design/topics/http-status-409
            topicGuidelines:
              href: /design/topics/http-status-409/guidelines
      _links:
        topic:
          href: /design/topics/http-status-409
    - references:
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-411
          name: HTTP Status 411
          description: When to use HTTP status 411
          _links:
            self:
              href: /design/topics/http-status-411
            topicGuidelines:
              href: /design/topics/http-status-411/guidelines
      _links:
        topic:
          href: /design/topics/http-status-411
    - references:
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-412
          name: HTTP Status 412
          description: When to use HTTP status 412
          _links:
            self:
              href: /design/topics/http-status-412
            topicGuidelines:
              href: /design/topics/http-status-412/guidelines
      _links:
        topic:
          href: /design/topics/http-status-412
    - references:
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-415
          name: HTTP Status 415
          description: When to use HTTP status 415
          _links:
            self:
              href: /design/topics/http-status-415
            topicGuidelines:
              href: /design/topics/http-status-415/guidelines
      _links:
        topic:
          href: /design/topics/http-status-415
    - references:
        - name: HTTP Status (Update Single Resource)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-2'
        - name: HTTP Status (Update Partial Single Resource)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#http-status-3'
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-422
          name: HTTP Status 422
          description: When to use HTTP status 422
          _links:
            self:
              href: /design/topics/http-status-422
            topicGuidelines:
              href: /design/topics/http-status-422/guidelines
      _links:
        topic:
          href: /design/topics/http-status-422
    - references:
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-500
          name: HTTP Status 500
          description: When to use HTTP status 500
          _links:
            self:
              href: /design/topics/http-status-500
            topicGuidelines:
              href: /design/topics/http-status-500/guidelines
      _links:
        topic:
          href: /design/topics/http-status-500
    - references:
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status-501
          name: HTTP Status 501
          description: When to use HTTP status 501
          _links:
            self:
              href: /design/topics/http-status-501
            topicGuidelines:
              href: /design/topics/http-status-501/guidelines
      _links:
        topic:
          href: /design/topics/http-status-501
    - references:
        - name: Error handling
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/error-handling/error-handling.md'
      _embedded:
        topic:
          id: http-status-standard-error
          name: Error format
          description: How to provide information about errors
          _links:
            self:
              href: /design/topics/http-status-standard-error
            topicGuidelines:
              href: /design/topics/http-status-standard-error/guidelines
      _links:
        topic:
          href: /design/topics/http-status-standard-error
    - references:
        - name: Mapping Response Codes For Success and Failure
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#mapping-response-codes-for-success-and-failure'
        - name: HTTP Status Codes
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-status-codes/http-status-codes.md'
      _embedded:
        topic:
          id: http-status
          name: HTTP Statuses
          description: General information about HTTP statuses usage
          _links:
            self:
              href: /design/topics/http-status
            topicGuidelines:
              href: /design/topics/http-status/guidelines
      _links:
        topic:
          href: /design/topics/http-status
    - references:
        - name: HTTP Verbs
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-verbs/http-verbs.md'
      _embedded:
        topic:
          id: http-methods-delete
          name: DELETE
          description: When to use HTTP method DELETE
          _links:
            self:
              href: /design/topics/http-methods-delete
            topicGuidelines:
              href: /design/topics/http-methods-delete/guidelines
      _links:
        topic:
          href: /design/topics/http-methods-delete
    - references:
        - name: HTTP Verbs
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-verbs/http-verbs.md'
        - name: Get List of resources
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#get-list-of-resources'
        - name: Read Single Resource
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#read-single-resource'
      _embedded:
        topic:
          id: http-methods-get
          name: GET
          description: When to use HTTP method GET
          _links:
            self:
              href: /design/topics/http-methods-get
            topicGuidelines:
              href: /design/topics/http-methods-get/guidelines
      _links:
        topic:
          href: /design/topics/http-methods-get
    - references:
        - name: HTTP Verbs
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-verbs/http-verbs.md'
        - name: Update Partial Single Resource
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#update-partial-single-resource'
      _embedded:
        topic:
          id: http-methods-patch
          name: PATCH
          description: When to use HTTP method PATCH
          _links:
            self:
              href: /design/topics/http-methods-patch
            topicGuidelines:
              href: /design/topics/http-methods-patch/guidelines
      _links:
        topic:
          href: /design/topics/http-methods-patch
    - references:
        - name: HTTP Verbs
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-verbs/http-verbs.md'
        - name: Create New Resource
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#create-new-resource'
        - name: Using POST (Search)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/search/search.md#using-post'
      _embedded:
        topic:
          id: http-methods-post
          name: POST
          description: When to use HTTP method POST
          _links:
            self:
              href: /design/topics/http-methods-post
            topicGuidelines:
              href: /design/topics/http-methods-post/guidelines
      _links:
        topic:
          href: /design/topics/http-methods-post
    - references:
        - name: HTTP Verbs
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-verbs/http-verbs.md'
        - name: Update Single Resource
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#update-single-resource'
        - name: Create New Resource - Consumer Supplied Identifier
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#create-new-resource---consumer-supplied-identifier'
      _embedded:
        topic:
          id: http-methods-put
          name: PUT
          description: When to use HTTP method PUT
          _links:
            self:
              href: /design/topics/http-methods-put
            topicGuidelines:
              href: /design/topics/http-methods-put/guidelines
      _links:
        topic:
          href: /design/topics/http-methods-put
    - references:
        - name: HTTP Verbs
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/http-verbs/http-verbs.md'
      _embedded:
        topic:
          id: http-methods
          name: HTTP methods
          description: General information about HTTP methods usage
          _links:
            self:
              href: /design/topics/http-methods
            topicGuidelines:
              href: /design/topics/http-methods/guidelines
      _links:
        topic:
          href: /design/topics/http-methods
    - references:
        - name: Expanding Resources Through Hypermedia Linking
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#expanding-resources-through-hypermedia-linking'
        - name: Hypermedia and REST
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/hypermedia-and-rest/hypermedia-and-rest.md'
        - name: Relationships and Sub-Resources
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/relationships-and-sub-resources/relationships-and-sub-resources.md'
        - name: Hypermedia Links (Pagination)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#hypermedia-links'
      _embedded:
        topic:
          id: hypermedia-read
          name: Hypermedia (read)
          description: How to use hypermedia to read data
          _links:
            self:
              href: /design/topics/hypermedia-read
            topicGuidelines:
              href: /design/topics/hypermedia-read/guidelines
      _links:
        topic:
          href: /design/topics/hypermedia-read
    - references:
        - name: Expanding Resources Through Hypermedia Linking
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#expanding-resources-through-hypermedia-linking'
        - name: Support Hypermedia
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/rest-principles/rest-principles.md#support-hypermedia'
        - name: Hypermedia and REST
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/hypermedia-and-rest/hypermedia-and-rest.md'
        - name: Relationships and Sub-Resources
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/relationships-and-sub-resources/relationships-and-sub-resources.md'
        - name: Hypermedia Links (Pagination)
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#hypermedia-links'
        - name: Hypermedia Response Format
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/response-format/response-format.md'
      _embedded:
        topic:
          id: hypermedia
          name: Hypermedia
          description: How to use hypermedia
          _links:
            self:
              href: /design/topics/hypermedia
            topicGuidelines:
              href: /design/topics/hypermedia/guidelines
      _links:
        topic:
          href: /design/topics/hypermedia
    - references:
        - name: Building Your Resource Taxonomy
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#building-your-resource-taxonomy'
        - name: Resource naming
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#resource-naming'
      _embedded:
        topic:
          id: naming
          name: Naming
          description: How to name things
          _links:
            self:
              href: /design/topics/naming
            topicGuidelines:
              href: /design/topics/naming/guidelines
      _links:
        topic:
          href: /design/topics/naming
    - references:
        - name: Create New Resource - Consumer Supplied Identifier
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#create-new-resource---consumer-supplied-identifier'
      _embedded:
        topic:
          id: resource-creation-with-id
          name: Create resource with a specific ID
          description: How to create resource with a provided id
          _links:
            self:
              href: /design/topics/resource-creation-with-id
            topicGuidelines:
              href: /design/topics/resource-creation-with-id/guidelines
      _links:
        topic:
          href: /design/topics/resource-creation-with-id
    - references:
        - name: Create New Resource
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#create-new-resource'
      _embedded:
        topic:
          id: resource-creation
          name: Create resource
          description: How to create resources
          _links:
            self:
              href: /design/topics/resource-creation
            topicGuidelines:
              href: /design/topics/resource-creation/guidelines
      _links:
        topic:
          href: /design/topics/resource-creation
    - references:
        - name: Delete Single Resource
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#delete-single-resource'
      _embedded:
        topic:
          id: resource-deletion
          name: Delete resource
          description: How to delete resources
          _links:
            self:
              href: /design/topics/resource-deletion
            topicGuidelines:
              href: /design/topics/resource-deletion/guidelines
      _links:
        topic:
          href: /design/topics/resource-deletion
    - references:
        - name: Composite Keys
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/faq/faq.md#composite-keys'
      _embedded:
        topic:
          id: resource-id
          name: Resource ID
          description: What is a resource ID and/or how it's built
          _links:
            self:
              href: /design/topics/resource-id
            topicGuidelines:
              href: /design/topics/resource-id/guidelines
      _links:
        topic:
          href: /design/topics/resource-id
    - references:
        - name: How to Handle Resource Relationships and Composition
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#how-to-handle-resource-relationships-and-composition'
        - name: Relationships and Sub-Resources
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/relationships-and-sub-resources/relationships-and-sub-resources.md'
      _embedded:
        topic:
          id: resource-relationships
          name: Relationships
          description: How to define and use relations between resources
          _links:
            self:
              href: /design/topics/resource-relationships
            topicGuidelines:
              href: /design/topics/resource-relationships/guidelines
      _links:
        topic:
          href: /design/topics/resource-relationships
    - references:
        - name: Update Single Resource
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#update-single-resource'
      _embedded:
        topic:
          id: resource-replacement
          name: Replace resource
          description: How to replace (or update fully) a resource
          _links:
            self:
              href: /design/topics/resource-replacement
            topicGuidelines:
              href: /design/topics/resource-replacement/guidelines
      _links:
        topic:
          href: /design/topics/resource-replacement
    - references:
        name: Dereference Relationships
        description: How to load a resource and its linked resources in one call
      _embedded:
        topic:
          id: resource-retrieve-dereference
          name: Dereference Relationships
          description: How to load a resource and its linked resources in one call
          _links:
            self:
              href: /design/topics/resource-retrieve-dereference
            topicGuidelines:
              href: /design/topics/resource-retrieve-dereference/guidelines
      _links:
        topic:
          href: /design/topics/resource-retrieve-dereference
    - references:
        - name: Field selection
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#field-selection'
      _embedded:
        topic:
          id: resource-retrieve-partial
          name: Retrieve resource partially
          description: How to retrieve partially a resource
          _links:
            self:
              href: /design/topics/resource-retrieve-partial
            topicGuidelines:
              href: /design/topics/resource-retrieve-partial/guidelines
      _links:
        topic:
          href: /design/topics/resource-retrieve-partial
    - references:
        - name: Read Single Resource
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#read-single-resource'
      _embedded:
        topic:
          id: resource-retrieve
          name: Retrieve resource
          description: How to retrieve a resource
          _links:
            self:
              href: /design/topics/resource-retrieve
            topicGuidelines:
              href: /design/topics/resource-retrieve/guidelines
      _links:
        topic:
          href: /design/topics/resource-retrieve
    - references:
        name: Resource's state
        description: How to change a resource's state/status (like processed/sent/paid/...)
      _embedded:
        topic:
          id: resource-state
          name: Resource's state
          description: How to change a resource's state/status (like processed/sent/paid/...)
          _links:
            self:
              href: /design/topics/resource-state
            topicGuidelines:
              href: /design/topics/resource-state/guidelines
      _links:
        topic:
          href: /design/topics/resource-state
    - references:
        - name: Update Partial Single Resource
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#update-partial-single-resource'
      _embedded:
        topic:
          id: resource-update-partial
          name: Update resource partially
          description: How to udate partially a resource
          _links:
            self:
              href: /design/topics/resource-update-partial
            topicGuidelines:
              href: /design/topics/resource-update-partial/guidelines
      _links:
        topic:
          href: /design/topics/resource-update-partial
    - references:
        - name: Update Single Resource
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#update-single-resource'
        - name: Update Partial Single Resource
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/collection-resources/collection-resources.md#update-partial-single-resource'
      _embedded:
        topic:
          id: resource-update
          name: Update resource
          description: How to update a resource
          _links:
            self:
              href: /design/topics/resource-update
            topicGuidelines:
              href: /design/topics/resource-update/guidelines
      _links:
        topic:
          href: /design/topics/resource-update
    - references:
        - name: URI Components
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/uri-components/uri-components.md'
      _embedded:
        topic:
          id: resource-url-format
          name: URL format
          description: How to design URLs
          _links:
            self:
              href: /design/topics/resource-url-format
            topicGuidelines:
              href: /design/topics/resource-url-format/guidelines
      _links:
        topic:
          href: /design/topics/resource-url-format
    - references:
        - name: Building Your Resource Taxonomy
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#building-your-resource-taxonomy'
        - name: Defining Resource Lifecycles
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#defining-resource-lifecycles'
        - name: Resources
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/resources/resources.md'
      _embedded:
        topic:
          id: resource
          name: Resource
          description: General informations about resources
          _links:
            self:
              href: /design/topics/resource
            topicGuidelines:
              href: /design/topics/resource/guidelines
      _links:
        topic:
          href: /design/topics/resource
    - references:
        - name: API clients MUST use an API Key
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/general-guidelines/general-guidelines.md#api-clients-must-use-an-api-key'
      _embedded:
        topic:
          id: security
          name: Security
          description: Security concerns
          _links:
            self:
              href: /design/topics/security
            topicGuidelines:
              href: /design/topics/security/guidelines
      _links:
        topic:
          href: /design/topics/security
    - references:
        - name: Security and Authentication
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/security-and-authentication/security-and-authentication.md'
      _embedded:
        topic:
          id: security-data
          name: Data privacy
          description: Data privacy concerns
          _links:
            self:
              href: /design/topics/security-data
            topicGuidelines:
              href: /design/topics/security-data/guidelines
      _links:
        topic:
          href: /design/topics/security-data
    - references:
        - name: Version
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/uri-components/uri-components.md#version'
      _embedded:
        topic:
          id: versioning
          name: Versionning
          description: How to handle API versionning
          _links:
            self:
              href: /design/topics/versioning
            topicGuidelines:
              href: /design/topics/versioning/guidelines
      _links:
        topic:
          href: /design/topics/versioning
  _embedded:
    guideline:
      id: haufe-api-styleguide
      title: Haufe API style guide
      type: github
      url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/readme.md'
      company: Haufe
      companyLogoUrl: /media/logos/haufe.png
      companyUrl: 'http://dev.haufe.com/'
      date: 2015-01-15T00:00:00.000Z
      reviewDate: 2016-08-31T00:00:00.000Z
      _links:
        self:
          href: /design/guidelines/haufe-api-styleguide
        guidelineTopics:
          href: /design/guidelines/haufe-api-styleguide/topics
  _links:
    self:
      href: /design/guidelines/haufe-api-styleguide/topics
    guideline:
      href: /design/guidelines/haufe-api-styleguide
---