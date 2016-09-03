---
layout: guideline
title: API Style Guide
permalink: /design/guidelines/paypal-api-style-guide
data:
  items:
    - references:
        - name: Time Selection
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#time-selection'
        - name: Complex Operation - Search
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#complex-operation---search'
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
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#paging'
        - name: Paging (Complex Operation - Search)
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#paging-1'
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
        - name: Collection Resources
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
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
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#sorting'
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
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
        - name: Sub-Resource Collection
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#sub-resource-collection'
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
        - name: Read-only resources
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#read-only-resources'
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
        - name: HTTP Status (Collections)
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status'
        - name: HTTP Status (Read Single Resource)
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status-1'
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
        - name: Update Single Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
        - name: Update Partial Single Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-partial-single-resource'
        - name: Delete Single Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#delete-single-resource'
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
        - name: HTTP Status (Collections)
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status'
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
        - name: HTTP Status (Collections)
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status'
        - name: HTTP Status (Read Single Resource)
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status-1'
        - name: Update Single Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
        - name: Delete Single Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#delete-single-resource'
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
        - name: Update Single Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
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
        - name: HTTP Status (Collections)
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status'
        - name: HTTP Status (Read Single Resource)
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status-1'
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
        - name: Collection Resources
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
        - name: Delete Single Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#delete-single-resource'
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
        - name: Collection Resources
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
        - name: HTTP Status (Read Single Resource)
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#http-status-1'
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
        - name: Collection Resources
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
        - name: Update Partial Single Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-partial-single-resource'
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
        - name: Collection Resources
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
        - name: Create New Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#create-new-resource'
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
        - name: Collection Resources
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
        - name: Update Single Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
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
        - name: Collection Resources
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
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
        - name: Paging Hypermedia Links
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#hypermedia-links'
        - name: Create New Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#create-new-resource'
          quote: Hypermedia links provide an easy way to get the URL of the newly created resource
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
        - name: Paging Hypermedia Links
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#hypermedia-links'
        - name: Create New Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#create-new-resource'
          quote: Hypermedia links provide an easy way to get the URL of the newly created resource
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
        - name: Collection Resources
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#collection-resources'
          quote: Collection resource names should be plural nouns
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
        - name: Filtering
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#filtering'
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
        name: Performance and bandwidth
        description: How to deal with high traffic or consumers with low bandwith
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
        - name: Complex Operation
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#complex-operation'
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
        - name: Create New Resource - Consumer Supplied Identifier
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#create-new-resource---consumer-supplied-identifier'
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
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#create-new-resource'
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
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#delete-single-resource'
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
        - name: Complex Operation - Composite
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#complex-operation---composite'
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
        - name: Update Single Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
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
        - name: Read Single Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#read-single-resource'
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
        - name: Complex Operation - Transient
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#complex-operation---transient'
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
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-partial-single-resource'
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
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-single-resource'
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
        - name: URL Components
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#uri-components'
        - name: Update Partial Single Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#update-partial-single-resource'
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
        - name: Read Single Resource
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#read-single-resource'
        - name: Sub-Resource Singleton
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#sub-resource-singleton'
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
        - name: Version
          url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md#version'
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
      id: paypal-api-style-guide
      title: API Style Guide
      type: github
      url: 'https://github.com/paypal/api-standards/blob/master/api-style-guide.md'
      company: PayPal
      companyLogoUrl: /media/logos/paypal.png
      companyUrl: 'https://developer.paypal.com/'
      date: 2016-08-11T00:00:00.000Z
      reviewDate: 2016-08-31T00:00:00.000Z
      _links:
        self:
          href: /design/guidelines/paypal-api-style-guide
        guidelineTopics:
          href: /design/guidelines/paypal-api-style-guide/topics
  _links:
    self:
      href: /design/guidelines/paypal-api-style-guide/topics
    guideline:
      href: /design/guidelines/paypal-api-style-guide
---