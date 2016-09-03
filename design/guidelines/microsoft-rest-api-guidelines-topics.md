---
layout: guideline
title: Microsoft REST API Guidelines
permalink: /design/guidelines/microsoft-rest-api-guidelines
data:
  items:
    - references:
        - name: Long running API faults
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#55-long-running-api-faults'
        - name: Long running operations
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#13-long-running-operations'
        - name: Operations resource
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1324-operations-resource'
        - name: Operation resource
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1325----operation-resource'
        - name: Operation tombstones
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1326-operation-tombstones'
        - name: 'The typical flow, polling'
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1327-the-typical-flow-polling'
        - name: 'The typical flow, push notifications'
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1328-the-typical-flow-push-notifications'
        - name: Retry-After
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1329-retry-after'
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
        - name: Filtering
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#97-filtering'
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
        - name: Big collections
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#94-big-collections'
        - name: Pagination
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#98-pagination'
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
        - name: Variable order rule
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#62-variable-order-rule'
        - name: Sorting collections
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#96-sorting-collections'
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
        - name: Collections
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#9-collections'
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
        - name: CORS
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#8-cors'
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
        - name: Guidelines for dates and times
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#112-guidelines-for-dates-and-times'
        - name: JSON serialization of dates and times
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#113-json-serialization-of-dates-and-times'
        - name: Durations
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#114-durations'
        - name: Intervals
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#115-intervals'
        - name: Repeating intervals
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#116-repeating-intervals'
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
        - name: Response Formats
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#710-response-formats'
        - name: JSON standardizations
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#11-json-standardizations'
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
        - name: Client Guidance
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#6-client-guidance'
        - name: Client library optional
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#712-client-library-optional'
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
        - name: Options and link headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#744-options-and-link-headers'
          quote: 'In addition, services SHOULD include a Link header (see RFC 5988) to point to documentation for the resource'
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
        - name: Errors
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#51-errors'
        - name: Faults
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#52-faults'
        - name: Long running API faults
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#55-long-running-api-faults'
        - name: Silent Fail Rule
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#63-silent-fail-rule'
        - name: Unsupported requests
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#15-unsupported-requests'
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
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#3-introduction'
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
        - name: Interpreting The Guidelines
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#4-interpreting-the-guidelines'
        - name: When to version
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#122-when-to-version'
        - name: Definition of a breaking change
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#123-definition-of-a-breaking-change'
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
        - name: Standard request headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#75-standard-request-headers'
          quote: 'If-Match, If-None-Match, If-Range'
        - name: Standard response headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#76-standard-response-headers'
          quote: ETag
        - name: Retention policy for operation results
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#133-retention-policy-for-operation-results'
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
        - name: Standard request headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#75-standard-request-headers'
          quote: Accept Content Type
        - name: Standard response headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#76-standard-response-headers'
          quote: Content Type
        - name: Clients-specified response format
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#7101-clients-specified-response-format'
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
        - name: POST
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#741-post'
          quote: POST operations SHOULD support the Location response header
        - name: Options and link headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#744-options-and-link-headers'
        - name: Standard request headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#75-standard-request-headers'
        - name: Standard response headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#76-standard-response-headers'
        - name: Custom Headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#77-custom-headers'
        - name: Specifying headers as query parameters
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#78-specifying-headers-as-query-parameters'
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
        - name: Error condition responses
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#7102-error-condition-responses'
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
        - name: Errors
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#51-errors'
        - name: Faults
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#52-faults'
        - name: HTTP Status Codes
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#711-http-status-codes'
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
        - name: Supported Methods
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
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
        - name: Supported Methods
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
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
        - name: Supported Methods
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
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
        - name: Supported Methods
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
        - name: Options and link headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#744-options-and-link-headers'
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
        - name: Supported Methods
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
        - name: PATCH
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#742-patch'
        - name: Creating resources via PATCH (UPSERT semantics)
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#743-creating-resources-via-patch-upsert-semantics'
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
        - name: Supported Methods
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
        - name: POST
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#741-post'
        - name: Changing collections
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#95-changing-collections'
        - name: POST (Long running operations)
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1322-post'
        - name: 'POST, hybrid model (Long running operations)'
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1323-post-hybrid-model'
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
        - name: Supported Methods
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
        - name: Changing collections
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#95-changing-collections'
        - name: PUT (Long running operations)
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1321-put'
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
        - name: Supported Methods
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#74-supported-methods'
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
        name: HTTP protocol
        description: General informations about HTTP protocol
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
        - name: Options and link headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#744-options-and-link-headers'
        - name: Big collections
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#94-big-collections'
          quote: the serialization payload MUST contain the opaque URL for the next page
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
        - name: 'The typical flow, push notifications'
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1328-the-typical-flow-push-notifications'
        - name: Push notifications via webhooks
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#14-push-notifications-via-webhooks'
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
        - name: Operations resource
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1324-operations-resource'
        - name: Operation resource
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1325----operation-resource'
        - name: Operation tombstones
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1326-operation-tombstones'
        - name: 'The typical flow, polling'
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1327-the-typical-flow-polling'
        - name: 'The typical flow, push notifications'
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1328-the-typical-flow-push-notifications'
        - name: Retry-After
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#1329-retry-after'
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
        - name: Delta queries
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#10-delta-queries'
      _embedded:
        topic:
          id: resource-change-tracking
          name: Track change
          description: How to track change on resources
          _links:
            self:
              href: /design/topics/resource-change-tracking
            topicGuidelines:
              href: /design/topics/resource-change-tracking/guidelines
      _links:
        topic:
          href: /design/topics/resource-change-tracking
    - references:
        - name: Creating resources via PATCH (UPSERT semantics)
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#743-creating-resources-via-patch-upsert-semantics'
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
        - name: POST
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#741-post'
        - name: Changing collections
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#95-changing-collections'
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
        - name: Canonical identifier
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#73-canonical-identifier'
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
        - name: Canonical identifier
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#73-canonical-identifier'
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
        name: Batch Bulk
        description: How to handle batch/bulk processing/creation/update/... (e.g. handle multiple resources at conce)
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
        - name: Standard request headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#75-standard-request-headers'
          quote: 'Prefer return=minimal, return=representation'
        - name: Standard response headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#76-standard-response-headers'
          quote: Preference-Applied
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
        - name: PATCH
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#742-patch'
        - name: Creating resources via PATCH (UPSERT semantics)
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#743-creating-resources-via-patch-upsert-semantics'
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
        - name: PATCH
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#742-patch'
        - name: Creating resources via PATCH (UPSERT semantics)
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#743-creating-resources-via-patch-upsert-semantics'
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
        - name: URL Structure
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#71-url-structure'
        - name: URL Length
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#72-url-length'
        - name: Collection URL patterns
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#93-collection-url-patterns'
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
        - name: Security
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#148-security'
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
        - name: PII parameters
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#79-pii-parameters'
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
        - name: Guidelines for existing services and versioning of services
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#42-guidelines-for-existing-services-and-versioning-of-services'
        - name: Versioning
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#12-versioning'
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
      id: microsoft-rest-api-guidelines
      title: Microsoft REST API Guidelines
      type: github
      url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md'
      company: Microsoft
      companyLogoUrl: /media/logos/microsoft.png
      companyUrl: 'https://opensource.microsoft.com/'
      date: 2016-07-19T00:00:00.000Z
      reviewDate: 2016-08-31T00:00:00.000Z
      _links:
        self:
          href: /design/guidelines/microsoft-rest-api-guidelines
        guidelineTopics:
          href: /design/guidelines/microsoft-rest-api-guidelines/topics
  _links:
    self:
      href: /design/guidelines/microsoft-rest-api-guidelines/topics
    guideline:
      href: /design/guidelines/microsoft-rest-api-guidelines
---