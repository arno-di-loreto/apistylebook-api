---
layout: guideline
title: White House Web API Standards
permalink: /design/guidelines/white-house-web-api-standards
data:
  items:
    - references:
        - name: Record Limits
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#record-limits'
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
        - name: JSONP
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#jsonp'
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
        - name: General guidelines for RESTful URLs
          quote: 'Formats should be in the form of api/v2/resource/{id}.json'
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
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
        - name: General guidelines for RESTful URLs
          quote: URL v. header
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
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
        - name: Error handling
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#error-handling'
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
        - name: Error handling
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#error-handling'
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
        - name: Error handling
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#error-handling'
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
        - name: Error handling
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#error-handling'
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
        - name: Error handling
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#error-handling'
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
        - name: General guidelines for RESTful URLs
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
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
        - name: General guidelines for RESTful URLs
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
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
        - name: General guidelines for RESTful URLs
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
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
        - name: General guidelines for RESTful URLs
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
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
        - name: HTTP verbs
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#http-verbs'
        - name: General guidelines for RESTful URLs
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
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
        - name: General guidelines for RESTful URLs
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
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
        - name: HTTP verbs
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#http-verbs'
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
        - name: HTTP verbs
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#http-verbs'
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
        - name: HTTP verbs
          quote: 'Bulk update, Delete all dogs'
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#http-verbs'
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
        - name: HTTP verbs
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#http-verbs'
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
        - name: HTTP verbs
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#http-verbs'
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
        - name: RESTful URLs
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#restful-urls'
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
        - name: General guidelines for RESTful URLs
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
        - name: Versions
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#versions'
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
      id: white-house-web-api-standards
      title: White House Web API Standards
      type: github
      url: 'https://github.com/WhiteHouse/api-standards'
      company: White House
      companyLogoUrl: /media/logos/whitehouse.png
      companyUrl: 'https://www.whitehouse.gov/developers'
      date: 2015-02-24T00:00:00.000Z
      reviewDate: 2016-08-18T00:00:00.000Z
      _links:
        self:
          href: /design/guidelines/white-house-web-api-standards
        guidelineTopics:
          href: /design/guidelines/white-house-web-api-standards/topics
  _links:
    self:
      href: /design/guidelines/white-house-web-api-standards/topics
    guideline:
      href: /design/guidelines/white-house-web-api-standards
---