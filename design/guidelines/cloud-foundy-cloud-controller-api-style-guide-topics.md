---
layout: guideline
title: Cloud Controller API v3 Style Guide (Proposal)
permalink: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide
data:
  items:
    - references:
        - name: Resources
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#resources'
        - name: Links
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#links'
        - name: Includind Related Resources
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#including-related-resources'
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
        - name: Resources
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#resources'
        - name: Links
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#links'
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
        - name: Links
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#links'
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
        - name: Requests
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#requests'
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
        - name: GET
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#get'
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
        - name: POST
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#post'
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
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#put'
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
        - name: DELETE
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#delete'
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
        - name: PATCH
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#patch'
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
        - name: Responses Codes
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#response-codes'
        - name: GET responses (Resource)
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#responses-resource'
        - name: GET responses (Collection)
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#responses-collection'
        - name: POST responses
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#responses'
        - name: PUT responses
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#responses-1'
        - name: PATCH responses
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#responses-2'
        - name: DELETE responses
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#responses-3'
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
        - name: Successful Requests
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#successful-requests'
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
        - name: Successful Requests
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#successful-requests'
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
        - name: Successful Requests
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#successful-requests'
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
        - name: Successful Requests
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#successful-requests'
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
        - name: Redirections
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#redirection'
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
        - name: Redirections
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#redirection'
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
        - name: Client Errors
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#client-errors'
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
        - name: Client Errors
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#client-errors'
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
        - name: Client Errors
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#client-errors'
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
        - name: Client Errors
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#client-errors'
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
        - name: Client Errors
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#client-errors'
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
        - name: Server Errors
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#server-errors'
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
        - name: Server Errors
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#server-errors'
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
        - name: Errors
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#errors'
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
        - name: Resources
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#resources'
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
        - name: Resources
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#resources'
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
        - name: URL Structure
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#url-structure'
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
        - name: GET
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#get'
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
        - name: Requesting Partiel Resources
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#requesting-partial-resources'
        - name: Nested Resources
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#nested-resources'
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
        - name: Includind Related Resources
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#including-related-resources'
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
        - name: POST
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#post'
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
        - name: PATCH
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#patch'
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
        - name: PATCH
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#patch'
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
        - name: DELETE
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#delete'
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
        - name: PUT
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#put'
        - name: Actions
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#actions'
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
        - name: Relationships
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#relationships'
        - name: Links
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#links'
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
        - name: Collections
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#collections'
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
        - name: GET
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#get'
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
        - name: Pagination
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#pagination'
        - name: Pagination of Related Resources
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#pagination-of-related-resources'
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
        - name: Filtering
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#filtering'
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
        - name: Query Parameters
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#query-parameters'
        - name: Field Names
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#field-names'
        - name: URL Structure
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#url-structure'
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
        - name: Query Parameters
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#query-parameters'
        - name: Field Names
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#field-names'
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
        - name: Query Parameters
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#query-parameters'
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
        - name: Asynchronicity
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#asynchronicity'
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
  _embedded:
    guideline:
      id: cloud-foundy-cloud-controller-api-style-guide
      title: Cloud Controller API v3 Style Guide (Proposal)
      type: github
      url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide'
      company: Cloud Foundry
      companyLogoUrl: /media/cloudfoundry.png
      companyUrl: 'https://www.cloudfoundry.org/'
      date: 2016-05-11T00:00:00.000Z
      reviewDate: 2016-08-18T00:00:00.000Z
      _links:
        self:
          href: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide
        guidelineTopics:
          href: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide/topics
  _links:
    self:
      href: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide/topics
    guideline:
      href: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide
---