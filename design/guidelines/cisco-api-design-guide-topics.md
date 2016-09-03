---
layout: guideline
title: API Design Guide
permalink: /design/guidelines/cisco-api-design-guide
data:
  items:
    - references:
        - name: 3.1 Security
          url: 'https://github.com/CiscoDevNet/api-design-guide#31-security'
        - name: 3.2 Authentication and Representation
          quote: 'The REST API MUST use OAuth2 implementation for user authentication and authorization, exclusively'
          url: 'https://github.com/CiscoDevNet/api-design-guide#32-authentication-and-authorization'
        - name: 3.6.8 Safe and Non-Safe Methods
          url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
        - name: 3.3 Representations
          quote: 3.3.3 A resource identifier labeled "url" MUST be present in all RESTful API resource representations
          url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
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
        - name: 3.3 Representations
          quote: 3.3.3 A resource identifier labeled "url" MUST be present in all RESTful API resource representations
          url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
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
        - name: 3.5.2 TrackingID Header
          url: 'https://github.com/CiscoDevNet/api-design-guide#352-trackingid-header'
      _embedded:
        topic:
          id: api-chaining
          name: API chaining
          description: How to chain API call in internal systems
          _links:
            self:
              href: /design/topics/api-chaining
            topicGuidelines:
              href: /design/topics/api-chaining/guidelines
      _links:
        topic:
          href: /design/topics/api-chaining
    - references:
        - name: 3.5.1 Standard Headers
          quote: 'ETag, If-Match, If-None-Match'
          url: 'https://github.com/CiscoDevNet/api-design-guide#351-standard-headers'
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
        - name: 3.3 Representations
          url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
        - name: 3.5.1 Standard Headers
          quote: 'Accept header, Content-Type header'
          url: 'https://github.com/CiscoDevNet/api-design-guide#351-standard-headers'
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
        - name: 3.5 HTTP Headers
          url: 'https://github.com/CiscoDevNet/api-design-guide#351-standard-headers'
        - name: 3.6.1 POST
          quote: Location header
          url: 'https://github.com/CiscoDevNet/api-design-guide#361-post'
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
        - name: 3.6 HTTP Verbs
          url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
        - name: REST Methods
          url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md#rest-methods'
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
        - name: 3.6.3 GET
          url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
        - name: 3.6.1 POST
          url: 'https://github.com/CiscoDevNet/api-design-guide#361-post'
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
        - name: 3.6.2 PUT
          url: 'https://github.com/CiscoDevNet/api-design-guide#362-put'
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
        - name: 3.6.4 DELETE
          url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
        - name: 3.6.5 PATCH
          url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
        - name: 3.6.6 HEAD
          url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
        - name: 3.6.7 OPTIONS
          url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
        - name: 3.7 Alternative Forms
          url: 'https://github.com/CiscoDevNet/api-design-guide#37-alternative-forms'
      _embedded:
        topic:
          id: http-methods-alternative
          name: Alternatives when only GET and POST are allowed
          description: What to do when only possible HTTP methods are POST and GET
          _links:
            self:
              href: /design/topics/http-methods-alternative
            topicGuidelines:
              href: /design/topics/http-methods-alternative/guidelines
      _links:
        topic:
          href: /design/topics/http-methods-alternative
    - references:
        - name: 3.9 Status Codes
          url: 'https://github.com/CiscoDevNet/api-design-guide#39-status-codes'
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
        - name: 3.9 Status Codes
          url: 'https://github.com/CiscoDevNet/api-design-guide#39-status-codes'
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
        - name: 3.9 Status Codes
          quote: 3.9.4 Documentation of response payloads MUST NOT reveal internal implementation details of the server.
          url: 'https://github.com/CiscoDevNet/api-design-guide#39-status-codes'
        - name: API Documentation
          document: null
          url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md#api-documentation'
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
        - name: 3 Guidelines
          quote: 'Reference Representation, Narrow Representation, Wide Representation'
          url: 'https://github.com/CiscoDevNet/api-design-guide#3-guidelines'
        - name: 3.3 Representations
          url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
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
        - name: 3.4 URL Format
          url: 'https://github.com/CiscoDevNet/api-design-guide#34-url-format'
        - name: URL Paths
          document: REST API Design Principles
          url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md#url-paths'
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
        - name: 3.4.2 User Scoped Endpoints
          url: 'https://github.com/CiscoDevNet/api-design-guide#342-user-scoped-endpoints'
      _embedded:
        topic:
          id: resource-id-semantic
          name: ID with semantic
          description: Using meaningful ids (like `me`)
          _links:
            self:
              href: /design/topics/resource-id-semantic
            topicGuidelines:
              href: /design/topics/resource-id-semantic/guidelines
      _links:
        topic:
          href: /design/topics/resource-id-semantic
    - references:
        - name: 3.6.3 GET
          url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
        - name: 3.6.3.6 Services MAY support partial retrieval of resource state
          quote: RFC-3986
          url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
        - name: null
          quote: 'If a service supports the fields parameter, then a value of @reference, @narrow, or @wide SHOULD...'
          url: null
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
        - name: 3.6.1 POST
          url: 'https://github.com/CiscoDevNet/api-design-guide#361-post'
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
        - name: 3.6.2 PUT
          url: 'https://github.com/CiscoDevNet/api-design-guide#362-put'
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
        - name: 3.6.2 PUT
          url: 'https://github.com/CiscoDevNet/api-design-guide#362-put'
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
        - name: 3.6.2 PUT
          url: 'https://github.com/CiscoDevNet/api-design-guide#362-put'
        - name: 3.6.5 PATCH
          url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
        - name: 3.6.5 PATCH
          url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
        - name: 3.6.4 DELETE
          url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
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
        - name: '3.11 Bulk, Batch, and Multi-Result Operations'
          url: 'https://github.com/CiscoDevNet/api-design-guide#311-bulk-batch-and-multi-result-operations'
      _embedded:
        topic:
          id: resource-multiple
          name: Batch Bulk
          description: How to handle batch/bulk processing/creation/update/... (e.g. handle multiple resources at conce)
          _links:
            self:
              href: /design/topics/resource-multiple
            topicGuidelines:
              href: /design/topics/resource-multiple/guidelines
      _links:
        topic:
          href: /design/topics/resource-multiple
    - references:
        - name: 3.8 Action Resources
          url: 'https://github.com/CiscoDevNet/api-design-guide#38-action-resources'
        - name: 3.6.1 POST
          url: 'https://github.com/CiscoDevNet/api-design-guide#361-post'
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
        - name: 3.6.3 GET
          url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
        - name: 3.6.3 GET
          url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
        - name: 3.6.3 GET
          url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
        - name: 3.3 Representations
          quote: '3.3.11 With regard to JSON representation property names, and URL query parameters, services SHOULD...'
          url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
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
        - name: 3.3 Representations
          url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
        - name: URL Paths
          document: REST API Design Principles
          url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md#url-paths'
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
        - name: 3.3 Representations
          quote: ... prefer the native JSON boolean type ...
          url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
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
        - name: 3.3 Representations
          quote: RFC-3339
          url: 'https://github.com/CiscoDevNet/api-design-guide#33-representations'
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
        - name: JSON Attributes
          url: 'https://github.com/CiscoDevNet/api-design-guide/blob/master/principles.md#json-attributes'
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
        - name: '*3.6.4.3 *The POST verb MAY be used to reverse the soft-delete of a resource, using an undelete parameter'
          url: 'https://github.com/CiscoDevNet/api-design-guide#36-http-verbs'
      _embedded:
        topic:
          id: undo
          name: Undo
          description: How to undo things
          _links:
            self:
              href: /design/topics/undo
            topicGuidelines:
              href: /design/topics/undo/guidelines
      _links:
        topic:
          href: /design/topics/undo
    - references:
        - name: 3.13 Versioning
          url: 'https://github.com/CiscoDevNet/api-design-guide#313-versioning'
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
      id: cisco-api-design-guide
      title: API Design Guide
      type: github
      url: 'https://github.com/CiscoDevNet/api-design-guide'
      company: Cisco
      companyLogoUrl: /media/logos/cisco.png
      companyUrl: 'http://developer.cisco.com/'
      date: 2015-08-21T00:00:00.000Z
      reviewDate: 2016-08-18T00:00:00.000Z
      _links:
        self:
          href: /design/guidelines/cisco-api-design-guide
        guidelineTopics:
          href: /design/guidelines/cisco-api-design-guide/topics
  _links:
    self:
      href: /design/guidelines/cisco-api-design-guide/topics
    guideline:
      href: /design/guidelines/cisco-api-design-guide
---