---
layout: guideline
title: Thoughts on RESTful API Design
permalink: /design/guidelines/redhat-thoughts-on-restful-api-design
data:
  items:
    - references:
        - name: Asynchronous Requests
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#asynchronous-requests'
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
    - references: null
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
        - name: Ranges Pagination
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#ranges-pagination'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: URLs
          url: 'http://restful-api-design.readthedocs.io/en/latest/urls.html'
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
        - name: Resource Data
          url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#resource-data'
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
        - name: Forms
          quote: '... without referring to external documentation, an API user does not know what data to provide to operations that take input.'
          url: 'http://restful-api-design.readthedocs.io/en/latest/forms.html'
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
        - name: Forms
          quote: '... without referring to external documentation, an API user does not know what data to provide to operations that take input.'
          url: 'http://restful-api-design.readthedocs.io/en/latest/forms.html'
      _embedded:
        topic:
          id: guiding-input
          name: Guiding inputs
          description: How to help consumers or end user to input relevant data
          _links:
            self:
              href: /design/topics/guiding-input
            topicGuidelines:
              href: /design/topics/guiding-input/guidelines
      _links:
        topic:
          href: /design/topics/guiding-input
    - references:
        - name: Representations
          url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#representations'
        - name: Content-Types
          url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#content-types'
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
        - name: Link Headers
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#link-headers'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: REST Metadata
          url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#rest-metadata'
        - name: Link Headers
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#link-headers'
        - name: Relationships
          url: 'http://restful-api-design.readthedocs.io/en/latest/relationships.html'
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
        - name: Forms
          quote: '... without referring to external documentation, an API user does not know what data to provide to operations that take input.'
          url: 'http://restful-api-design.readthedocs.io/en/latest/forms.html'
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
        - name: REST Metadata
          url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#rest-metadata'
        - name: Link Headers
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#link-headers'
        - name: Relationships
          url: 'http://restful-api-design.readthedocs.io/en/latest/relationships.html'
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
        - name: Notifications
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#notifications'
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
        - name: Actions
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#actions'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: REST Metadata
          url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html#rest-metadata'
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
        - name: PATCH vs PUT
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#patch-vs-put'
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
        - name: Relationships
          url: 'http://restful-api-design.readthedocs.io/en/latest/relationships.html'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: Methods
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html'
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
        - name: URLs
          url: 'http://restful-api-design.readthedocs.io/en/latest/urls.html'
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
        - name: Resources
          url: 'http://restful-api-design.readthedocs.io/en/latest/resources.html'
        - name: URLs
          url: 'http://restful-api-design.readthedocs.io/en/latest/urls.html'
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
  _embedded:
    guideline:
      id: redhat-thoughts-on-restful-api-design
      title: Thoughts on RESTful API Design
      type: website
      url: 'http://restful-api-design.readthedocs.io/en/latest/'
      company: Red Hat
      companyLogoUrl: /media/logos/redhat.png
      companyUrl: 'https://www.redhat.com/'
      date: 2012-11-15T00:00:00.000Z
      reviewDate: 2016-08-18T00:00:00.000Z
      _links:
        self:
          href: /design/guidelines/redhat-thoughts-on-restful-api-design
        guidelineTopics:
          href: /design/guidelines/redhat-thoughts-on-restful-api-design/topics
  _links:
    self:
      href: /design/guidelines/redhat-thoughts-on-restful-api-design/topics
    guideline:
      href: /design/guidelines/redhat-thoughts-on-restful-api-design
---