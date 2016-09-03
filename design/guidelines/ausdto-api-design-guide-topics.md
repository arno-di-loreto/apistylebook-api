---
layout: guideline
title: API Design Guide
permalink: /design/guidelines/ausdto-api-design-guide
data:
  items:
    - references:
        - name: Batching results
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/batching_results.html'
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
        - name: Support cross-domain mashups with CORS
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/cors.html'
      _embedded:
        topic:
          id: cors
          name: CORS
          description: How to deal with CORS
          _links:
            self:
              href: /design/topics/cors
            topicGuidelines:
              href: /design/topics/cors/guidelines
      _links:
        topic:
          href: /design/topics/cors
    - references:
        - name: Empathy
          url: 'https://apiguide.readthedocs.io/en/latest/principles/empathy.html'
        - name: Errors
          url: 'https://apiguide.readthedocs.io/en/latest/principles/errors.html'
        - name: Endpoint Stability
          url: 'https://apiguide.readthedocs.io/en/latest/principles/availability.html'
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
        - name: Discoverability
          url: 'https://apiguide.readthedocs.io/en/latest/principles/discoverability.html'
        - name: Document your API
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/documentation.html'
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
        - name: Register your API
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/advertise.html'
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
        - name: Formats
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#formats'
        - name: API Payload format encoding
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#api-payload-format-encoding'
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
        - name: GET /magazines
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#get--magazines'
        - name: PUT /magazines
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#put--magazines'
        - name: DELETE /magazines
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#delete--magazines'
        - name: DELETE /magazines/1234
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#delete--magazines-1234'
        - name: HEAD /magazines
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#head--magazines'
        - name: HEAD /magazines/1234
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#head--magazines-1234'
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
        - name: Use HTTP methods and status codes
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#use-http-methods-and-status-codes'
        - name: PUT /magazines/1234
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#put--magazines-1234'
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
        - name: GET /magazines
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#get--magazines'
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
        - name: Use HTTP methods and status codes
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#use-http-methods-and-status-codes'
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
        - name: HTTP response principles
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#http-response-principles'
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
        - name: DELETE /magazines
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#delete--magazines'
        - name: DELETE /magazines/1234
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#delete--magazines-1234'
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
        - name: GET /magazines
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#get--magazines'
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
        - name: HEAD /magazines
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#head--magazines'
        - name: HEAD /magazines/1234
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#head--magazines-1234'
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
        - name: POST /magazines
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#post--magazines'
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
        - name: PUT /magazines
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#put--magazines'
        - name: PUT /magazines/1234
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#put--magazines-1234'
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
        - name: Use HTTP methods and status codes
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_HTTP_methods.html#use-http-methods-and-status-codes'
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
        - name: Management state with HATEOAS
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/hateos.html'
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
        - name: Management state with HATEOAS
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/hateos.html'
      _embedded:
        topic:
          id: hypermedia-write
          name: Hypermedia (write)
          description: How to use hypermedia to write data
          _links:
            self:
              href: /design/topics/hypermedia-write
            topicGuidelines:
              href: /design/topics/hypermedia-write/guidelines
      _links:
        topic:
          href: /design/topics/hypermedia-write
    - references:
        - name: Management state with HATEOAS
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/hateos.html'
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
        - name: Granularity
          url: 'https://apiguide.readthedocs.io/en/latest/principles/granularity.html'
        - name: Functionality
          url: 'https://apiguide.readthedocs.io/en/latest/principles/coverage.html'
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
        - name: Management state with HATEOAS
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/hateos.html'
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
        - name: URL Depth
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#url-depth'
        - name: Good RESTful URL examples
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#good-restful-url-examples'
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
        - name: Privacy and security
          url: 'https://apiguide.readthedocs.io/en/latest/principles/security.html'
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
        - name: Privacy and security
          url: 'https://apiguide.readthedocs.io/en/latest/principles/security.html'
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
        - name: Versioning
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/use_RESTful_urls.html#versioning'
        - name: Use versions
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/versioning.html'
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
      id: ausdto-api-design-guide
      title: API Design Guide
      type: website
      url: 'https://apiguide.readthedocs.io/en/latest/index.html'
      company: Australian Digital Transformation Office
      companyLogoUrl: /media/logos/ausdto.png
      companyUrl: 'https://www.dto.gov.au/'
      date: 2015-10-20T00:00:00.000Z
      reviewDate: 2016-08-18T00:00:00.000Z
      _links:
        self:
          href: /design/guidelines/ausdto-api-design-guide
        guidelineTopics:
          href: /design/guidelines/ausdto-api-design-guide/topics
  _links:
    self:
      href: /design/guidelines/ausdto-api-design-guide/topics
    guideline:
      href: /design/guidelines/ausdto-api-design-guide
---