---
layout: guideline
title: RESTFul API Guidelines
permalink: /design/guidelines/zalando-restful-api-guidelines
data:
  items:
    - references:
        - name: Limit of Resources
          url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#should-limit-of-resources'
          quote: a typical range of resources for a well-designed API is between 4 and 8
      _embedded:
        topic:
          id: api-counts
          name: API counts
          description: How many endpoints/resources in an API?
          _links:
            self:
              href: /design/topics/api-counts
            topicGuidelines:
              href: /design/topics/api-counts/guidelines
      _links:
        topic:
          href: /design/topics/api-counts
    - references:
        - name: Events
          url: 'http://zalando.github.io/restful-api-guidelines/events/events.html'
      _embedded:
        topic:
          id: asynchronicity
          name: Asynchronicity
          description: How to handle long operations
          _links:
            self:
              href: /design/topics/asynchronicity
            topicGuidelines:
              href: /design/topics/asynchronicity/guidelines
      _links:
        topic:
          href: /design/topics/asynchronicity
    - references:
        - name: Use Conventional Query Strings
          quote: q — default query parameter
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
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
        - name: Use Conventional Query Strings
          quote: 'limit, cursor, offset'
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
        - name: Pagination
          url: 'http://zalando.github.io/restful-api-guidelines/pagination/Pagination.html'
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
        - name: GET
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#get'
          quote: reads a resource or set of resource instances
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
        - name: Use Conventional Query Strings
          quote: sort — comma-separated list of fields to sort
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
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
        - name: Resources
          url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html'
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
        - name: 'Standards could be used for Language, Country and Currency'
          url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#could-standards-could-be-used-for-language-country-and-currency'
        - name: 'Use Standards for Country, Language and Currency Codes'
          url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#could-use-standards-for-country-language-and-currency-codes'
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
        - name: Date property values should conform to RFC 3399
          url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#should-date-property-values-should-conform-to-rfc-3399'
        - name: Time durations and intervals could conform to ISO 8601
          url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#could-time-durations-and-intervals-could-conform-to-iso-8601'
        - name: Use Standard Date and Time Formats
          url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#must-use-standard-date-and-time-formats'
        - name: HTTP headers
          url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#http-headers'
          quote: Use the HTTP date format defined in RFC 7231
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
        - name: Property values
          url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#property-values'
        - name: Null values should have their fields removed
          url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#should-null-values-should-have-their-fields-removed'
        - name: Boolean property values must not be null
          url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#must-boolean-property-values-must-not-be-null'
        - name: Empty array values should not be null
          url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#should-empty-array-values-should-not-be-null'
      _embedded:
        topic:
          id: data-format-null
          name: Null data
          description: How to deal with null data
          _links:
            self:
              href: /design/topics/data-format-null
            topicGuidelines:
              href: /design/topics/data-format-null/guidelines
      _links:
        topic:
          href: /design/topics/data-format-null
    - references:
        - name: Property Values
          url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#property-values'
        - name: Date property values should conform to RFC 3399
          url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#should-date-property-values-should-conform-to-rfc-3399'
        - name: Time durations and intervals could conform to ISO 8601
          url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#could-time-durations-and-intervals-could-conform-to-iso-8601'
        - name: Data Formats
          url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html'
        - name: Common Data Objects
          url: 'http://zalando.github.io/restful-api-guidelines/common-data-objects/CommonDataObjects.html'
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
        - name: Provide External Documentation
          url: 'http://zalando.github.io/restful-api-guidelines/general-guidelines/GeneralGuidelines.html#should-provide-external-documentation'
        - name: Reflect Deprecation in API Definition
          url: 'http://zalando.github.io/restful-api-guidelines/deprecation/Deprecation.html#must-reflect-deprecation-in-api-definition'
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
        - name: Design Principles
          url: 'http://zalando.github.io/restful-api-guidelines/design-principles/DesignPrinciples.html'
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
        - name: API First
          url: 'http://zalando.github.io/restful-api-guidelines/general-guidelines/GeneralGuidelines.html#must-api-first-define-apis-using-openapi'
        - name: Deprecation
          url: 'http://zalando.github.io/restful-api-guidelines/deprecation/Deprecation.html'
        - name: API Discovery
          url: 'http://zalando.github.io/restful-api-guidelines/api-discovery/ApiDiscovery.html'
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
        - name: Support the ETag Header
          url: 'http://zalando.github.io/restful-api-guidelines/performance/Performance.html#could-support-the-etag-header'
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
        - name: Use Media Type Versioning
          url: 'http://zalando.github.io/restful-api-guidelines/compatibility/Compatibility.html#must-use-media-type-versioning'
        - name: Modify the Content-Type for Embedded Resources
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-modify-the-contenttype-for-embedded-resources'
        - name: Use Application-Specific Content Types
          url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#could-use-applicationspecific-content-types'
      _embedded:
        topic:
          id: http-content-negotiation
          name: Content negociation and media types
          description: 'How to describe your API data format and/or propose different formats (like json, yaml, xml atom, ...)'
          _links:
            self:
              href: /design/topics/http-content-negotiation
            topicGuidelines:
              href: /design/topics/http-content-negotiation/guidelines
      _links:
        topic:
          href: /design/topics/http-content-negotiation
    - references:
        - name: You Must Hyphenate HTTP Headers
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#must-you-must-hyphenate-http-headers'
        - name: Prefer Hyphenated-Pascal-Case for HTTP header Fields
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#should-prefer-hyphenatedpascalcase-for-http-header-fields'
        - name: Use Standardized Headers
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-standardized-headers'
        - name: Use 429 with Headers for Rate Limits
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must-use-429-with-headers-for-rate-limits'
        - name: Do Not Use Link Headers with JSON entities
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-do-not-use-link-headers-with-json-entities'
        - name: HTTP headers
          url: 'http://zalando.github.io/restful-api-guidelines/data-formats/DataFormats.html#http-headers'
          quote: Use the HTTP date format defined in RFC 7231
        - name: Common Headers
          url: 'http://zalando.github.io/restful-api-guidelines/headers/CommonHeaders.html'
        - name: Proprietary Headers
          url: 'http://zalando.github.io/restful-api-guidelines/headers/ProprietaryHeaders.html'
        - name: Add a Warning Header to Responses
          url: 'http://zalando.github.io/restful-api-guidelines/deprecation/Deprecation.html#should-add-a-warning-header-to-responses'
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
        - name: Success Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#success-codes'
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
        - name: Success Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#success-codes'
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
        - name: Success Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#success-codes'
      _embedded:
        topic:
          id: http-status-202
          name: HTTP Status 202
          description: When to use HTTP status 202
          _links:
            self:
              href: /design/topics/http-status-202
            topicGuidelines:
              href: /design/topics/http-status-202/guidelines
      _links:
        topic:
          href: /design/topics/http-status-202
    - references:
        - name: Success Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#success-codes'
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
        - name: Redirection Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#redirection-codes'
      _embedded:
        topic:
          id: http-status-301
          name: HTTP Status 301
          description: When to use HTTP status 301
          _links:
            self:
              href: /design/topics/http-status-301
            topicGuidelines:
              href: /design/topics/http-status-301/guidelines
      _links:
        topic:
          href: /design/topics/http-status-301
    - references:
        name: HTTP Status 302
        description: When to use HTTP status 302
      _embedded:
        topic:
          id: http-status-302
          name: HTTP Status 302
          description: When to use HTTP status 302
          _links:
            self:
              href: /design/topics/http-status-302
            topicGuidelines:
              href: /design/topics/http-status-302/guidelines
      _links:
        topic:
          href: /design/topics/http-status-302
    - references:
        - name: Redirection Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#redirection-codes'
      _embedded:
        topic:
          id: http-status-303
          name: HTTP Status 303
          description: When to use HTTP status 303
          _links:
            self:
              href: /design/topics/http-status-303
            topicGuidelines:
              href: /design/topics/http-status-303/guidelines
      _links:
        topic:
          href: /design/topics/http-status-303
    - references:
        - name: Redirection Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#redirection-codes'
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
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
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
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
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
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
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
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
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
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
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
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
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
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
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
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
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
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
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
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
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
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
      _embedded:
        topic:
          id: http-status-423
          name: HTTP Status 423
          description: When to use HTTP status 423
          _links:
            self:
              href: /design/topics/http-status-423
            topicGuidelines:
              href: /design/topics/http-status-423/guidelines
      _links:
        topic:
          href: /design/topics/http-status-423
    - references:
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
      _embedded:
        topic:
          id: http-status-428
          name: HTTP Status 428
          description: When to use HTTP status 428
          _links:
            self:
              href: /design/topics/http-status-428
            topicGuidelines:
              href: /design/topics/http-status-428/guidelines
      _links:
        topic:
          href: /design/topics/http-status-428
    - references:
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
        - name: Use 429 with Headers for Rate Limits
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must-use-429-with-headers-for-rate-limits'
      _embedded:
        topic:
          id: http-status-429
          name: HTTP Status 429
          description: When to use HTTP status 429
          _links:
            self:
              href: /design/topics/http-status-429
            topicGuidelines:
              href: /design/topics/http-status-429/guidelines
      _links:
        topic:
          href: /design/topics/http-status-429
    - references:
        - name: Server Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#server-side-error-codes'
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
        - name: Server Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#server-side-error-codes'
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
        - name: Server Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#server-side-error-codes'
      _embedded:
        topic:
          id: http-status-503
          name: HTTP Status 503
          description: When to use HTTP status 503
          _links:
            self:
              href: /design/topics/http-status-503
            topicGuidelines:
              href: /design/topics/http-status-503/guidelines
      _links:
        topic:
          href: /design/topics/http-status-503
    - references:
        - name: Providing Error Documentation
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must-providing-error-documentation'
        - name: Use Problem JSON
          url: 'http://zalando.github.io/restful-api-guidelines/common-data-objects/CommonDataObjects.html#must-use-problem-json'
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
        - name: Use Meaningful HTTP Status Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must-use-meaningful-http-status-codes'
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
        - name: DELETE
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#delete'
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
        - name: GET
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#get'
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
        - name: HEAD
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#head'
      _embedded:
        topic:
          id: http-methods-head
          name: HEAD
          description: When to use HTTP method HEAD
          _links:
            self:
              href: /design/topics/http-methods-head
            topicGuidelines:
              href: /design/topics/http-methods-head/guidelines
      _links:
        topic:
          href: /design/topics/http-methods-head
    - references:
        - name: OPTIONS
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#options'
      _embedded:
        topic:
          id: http-methods-options
          name: OPTIONS
          description: When to use HTTP method OPTION
          _links:
            self:
              href: /design/topics/http-methods-options
            topicGuidelines:
              href: /design/topics/http-methods-options/guidelines
      _links:
        topic:
          href: /design/topics/http-methods-options
    - references:
        - name: PATCH
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#patch'
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
        - name: POST
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#post'
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
        - name: PUT
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#put'
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
        - name: Use HTTP Methods Correctly
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must-use-http-methods-correctly'
        - name: HTTP Methods must Fulfill Safeness and Idempotency Properties
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must--http-methods-must-fulfill-safeness-and-idempotency-properties'
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
        - name: HTTP
          description: 'http://zalando.github.io/restful-api-guidelines/http/Http.html'
      _embedded:
        topic:
          id: http
          name: HTTP protocol
          description: General informations about HTTP protocol
          _links:
            self:
              href: /design/topics/http
            topicGuidelines:
              href: /design/topics/http/guidelines
      _links:
        topic:
          href: /design/topics/http
    - references:
        - name: Use Pagination Links Where Applicable
          url: 'http://zalando.github.io/restful-api-guidelines/pagination/Pagination.html#could-use-pagination-links-where-applicable'
        - name: Use a well-defined subset of HAL
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-use-a-welldefined-subset-of-hal'
        - name: Use Custom Link Relations
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#could-use-custom-link-relations'
        - name: Do Not Use Link Headers with JSON entities
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-do-not-use-link-headers-with-json-entities'
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
        - name: Use Pagination Links Where Applicable
          url: 'http://zalando.github.io/restful-api-guidelines/pagination/Pagination.html#could-use-pagination-links-where-applicable'
        - name: Hypermedia
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html'
        - name: Use a well-defined subset of HAL
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-use-a-welldefined-subset-of-hal'
        - name: Do Not Use Link Headers with JSON entities
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-do-not-use-link-headers-with-json-entities'
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
        - name: Write APIs in U.S. English
          url: 'http://zalando.github.io/restful-api-guidelines/general-guidelines/GeneralGuidelines.html#must-write-apis-in-us-english'
      _embedded:
        topic:
          id: naming-language
          name: language
          description: Which language(s) use when designing an API
          _links:
            self:
              href: /design/topics/naming-language
            topicGuidelines:
              href: /design/topics/naming-language/guidelines
      _links:
        topic:
          href: /design/topics/naming-language
    - references:
        - name: Property names must be snake_case
          url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#must-property-names-must-be-snakecase-and-never-camelcase'
      _embedded:
        topic:
          id: naming-case
          name: Case
          description: 'Which case (lowercase, camelCase, ...) to use and when'
          _links:
            self:
              href: /design/topics/naming-case
            topicGuidelines:
              href: /design/topics/naming-case/guidelines
      _links:
        topic:
          href: /design/topics/naming-case
    - references:
        - name: Property naming
          url: 'http://zalando.github.io/restful-api-guidelines/json-guidelines/JsonGuidelines.html#property-naming'
        - name: API Naming
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html'
        - name: Use Domain-Specific Resource Names
          url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#must-use-domainspecific-resource-names'
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
        - name: Events
          url: 'http://zalando.github.io/restful-api-guidelines/events/events.html'
      _embedded:
        topic:
          id: notifications-server-events
          name: Notifying API consumers
          description: How to send events or notifications to API consumers
          _links:
            self:
              href: /design/topics/notifications-server-events
            topicGuidelines:
              href: /design/topics/notifications-server-events/guidelines
      _links:
        topic:
          href: /design/topics/notifications-server-events
    - references:
        name: Performance
        url: 'http://zalando.github.io/restful-api-guidelines/performance/Performance.html'
      _embedded:
        topic:
          id: performance
          name: Performance and bandwidth
          description: How to deal with high traffic or consumers with low bandwith
          _links:
            self:
              href: /design/topics/performance
            topicGuidelines:
              href: /design/topics/performance/guidelines
      _links:
        topic:
          href: /design/topics/performance
    - references:
        - name: Query parameters must be snake_case (never camelCase)
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#must-query-parameters-must-be-snakecase-never-camelcase'
        - name: Use Conventional Query Strings
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
      _embedded:
        topic:
          id: query-parameter
          name: Query parameters
          description: How to use query parameters
          _links:
            self:
              href: /design/topics/query-parameter
            topicGuidelines:
              href: /design/topics/query-parameter/guidelines
      _links:
        topic:
          href: /design/topics/query-parameter
    - references:
        - name: Avoid Actions — Think About Resources
          url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#must-avoid-actions-—-think-about-resources'
      _embedded:
        topic:
          id: resource-action
          name: Action resource
          description: How to use action resource (e.g. resources like /cancel or /approve)
          _links:
            self:
              href: /design/topics/resource-action
            topicGuidelines:
              href: /design/topics/resource-action/guidelines
      _links:
        topic:
          href: /design/topics/resource-action
    - references:
        - name: POST
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#post'
          quote: creates a resource instance
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
        - name: DELETE
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#delete'
          quote: deletes a resource instance
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
        - name: Use a well-defined subset of HAL
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-use-a-welldefined-subset-of-hal'
        - name: Use Custom Link Relations
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#could-use-custom-link-relations'
        - name: Do Not Use Link Headers with JSON entities
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-do-not-use-link-headers-with-json-entities'
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
        - name: PUT
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#put'
          quote: fully uploads an entity
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
        - name: Use Conventional Query Strings
          quote: embed — to expand embedded entities
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
        - name: Define useful resources
          url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#should-define-useful-resources'
        - name: Allow Optional Embedding of Sub-Resources
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#should-allow-optional-embedding-of-subresources'
        - name: Modify the Content-Type for Embedded Resources
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-modify-the-contenttype-for-embedded-resources'
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
        - name: Use Conventional Query Strings
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
          quote: fields — to retrieve a subset of fields
        - name: Define useful resources
          url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#should-define-useful-resources'
        - name: Support Filtering of Resource Fields
          url: 'http://zalando.github.io/restful-api-guidelines/performance/Performance.html#should-support-filtering-of-resource-fields'
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
        - name: GET
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#get'
          quote: reads a resource or set of resource instances
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
        - name: PATCH
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#patch'
          quote: only a specific subset of resource fields are replaced
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
        - name: PUT
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#put'
        - name: PATCH
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#patch'
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
        - name: Path segments must be lowercase separate words with hyphens
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#must-path-segments-must-be-lowercase-separate-words-with-hyphens'
        - name: Always Pluralize Resource Names
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#must-always-pluralize-resource-names'
        - name: First Path segment May be /api
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-first-path-segment-may-be-api'
        - name: Avoid Trailing Slashes
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#must-avoid-trailing-slashes'
        - name: Limit of Sub-Resource Levels
          url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#should-limit-of-subresource-levels'
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
        - name: resources
          url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html'
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
        - name: Security
          url: 'http://zalando.github.io/restful-api-guidelines/security/Security.html'
        - name: Secure Endpoints with OAuth 2.0
          url: 'http://zalando.github.io/restful-api-guidelines/security/Security.html#must-secure-endpoints-with-oauth-20'
        - name: Define and Assign Access Rights (Scopes)
          url: 'http://zalando.github.io/restful-api-guidelines/security/Security.html#must-define-and-assign-access-rights-scopes'
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
        - name: Compatibility
          url: 'http://zalando.github.io/restful-api-guidelines/compatibility/Compatibility.html'
        - name: Don’t Break Backward Compatibility
          url: 'http://zalando.github.io/restful-api-guidelines/compatibility/Compatibility.html#must-dont-break-backward-compatibility'
        - name: Avoid Versioning
          url: 'http://zalando.github.io/restful-api-guidelines/compatibility/Compatibility.html#should-avoid-versioning'
        - name: Use Media Type Versioning
          url: 'http://zalando.github.io/restful-api-guidelines/compatibility/Compatibility.html#must-use-media-type-versioning'
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
      id: zalando-restful-api-guidelines
      title: RESTFul API Guidelines
      type: website
      url: 'http://zalando.github.io/restful-api-guidelines/'
      company: Zalando
      companyLogoUrl: /media/logos/zalando.png
      companyUrl: 'https://tech.zalando.de/'
      date: 2016-01-22T00:00:00.000Z
      reviewDate: 2016-08-28T00:00:00.000Z
      _links:
        self:
          href: /design/guidelines/zalando-restful-api-guidelines
        guidelineTopics:
          href: /design/guidelines/zalando-restful-api-guidelines/topics
  _links:
    self:
      href: /design/guidelines/zalando-restful-api-guidelines/topics
    guideline:
      href: /design/guidelines/zalando-restful-api-guidelines
---