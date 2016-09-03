---
layout: guideline
title: HTTP API Design Guide
permalink: /design/guidelines/heroku-http-api-design-guide
data:
  items:
    - references:
        - name: Divide Large Responses Across Requests with Ranges
          description: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/divide-large-responses-across-requests-with-ranges.html'
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
        - name: Provide standard timestamps
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-standard-timestamps.html'
        - name: Use UTC times formatted in ISO8601
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/use-utc-times-formatted-in-iso8601.html'
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
        - name: Accept serialized JSON in request bodies
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/accept-serialized-json-in-request-bodies.html'
        - name: Provide standard timestamps
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-standard-timestamps.html'
        - name: Nest foreign key relations
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/nest-foreign-key-relations.html'
        - name: Keep JSON minified in all responses
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/keep-json-minified-in-all-responses.html'
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
        - name: Provide Request-Ids for Introspection
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/provide-request-ids-for-introspection.html'
      _embedded:
        topic:
          id: debug-diagnose
          name: Debug and diagnose
          description: How to provide informations to debug and diagnose
          _links:
            self:
              href: /design/topics/debug-diagnose
            topicGuidelines:
              href: /design/topics/debug-diagnose/guidelines
      _links:
        topic:
          href: /design/topics/debug-diagnose
    - references:
        - name: Provide machine-readable JSON schema
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/artifacts/provide-machine-readable-json-schema.html'
        - name: Provide human-readable docs
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/artifacts/provide-human-readable-docs.html'
        - name: Provide executable examples
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/artifacts/provide-executable-examples.html'
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
        - name: Separate Concerns
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/separate-concerns.html'
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
        - name: Support ETags for Caching
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/support-etags-for-caching.html'
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
        - name: Require Versioning in the Accepts Header
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/require-versioning-in-the-accepts-header.html'
        - name: Support ETags for Caching
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/support-etags-for-caching.html'
        - name: Provide Request-Ids for Introspection
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/provide-request-ids-for-introspection.html'
        - name: Divide Large Responses Across Requests with Ranges
          description: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/divide-large-responses-across-requests-with-ranges.html'
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
        - name: Return appropriate status codes
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
        - name: Return appropriate status codes
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
        - name: Return appropriate status codes
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
        - name: Return appropriate status codes
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
      _embedded:
        topic:
          id: http-status-206
          name: HTTP Status 206
          description: When to use HTTP status 206
          _links:
            self:
              href: /design/topics/http-status-206
            topicGuidelines:
              href: /design/topics/http-status-206/guidelines
      _links:
        topic:
          href: /design/topics/http-status-206
    - references:
        - name: Return appropriate status codes
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
        - name: Require Secure Connections
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/require-secure-connections.html'
        - name: Return appropriate status codes
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
        - name: Return appropriate status codes
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
        - name: Return appropriate status codes
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
        - name: Return appropriate status codes
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
        - name: Generate structured errors
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/generate-structured-errors.html'
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
        - name: Return appropriate status codes
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
        - name: Downcase paths and attributes
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/downcase-paths-and-attributes.html'
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
        - name: Resource names
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/resource-names.html'
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
        - name: Keep JSON minified in all responses
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/keep-json-minified-in-all-responses.html'
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
        - name: Show rate limit status
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/show-rate-limit-status.html'
      _embedded:
        topic:
          id: rate-limiting
          name: Rate limiting
          description: !<tag:yaml.org,2002:js/undefined> ''
          _links:
            self:
              href: /design/topics/rate-limiting
            topicGuidelines:
              href: /design/topics/rate-limiting/guidelines
      _links:
        topic:
          href: /design/topics/rate-limiting
    - references:
        - name: Actions
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/actions.html'
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
        - name: Provide full resources where available
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-full-resources-where-available.html'
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
        - name: Provide full resources where available
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-full-resources-where-available.html'
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
        - name: Support non-id dereferencing for convenience
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/support-non-id-dereferencing-for-convenience.html'
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
        - name: Support non-id dereferencing for convenience
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/support-non-id-dereferencing-for-convenience.html'
        - name: Provide resource (UU)IDs
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-resource-uuids.html'
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
        - name: Nest foreign key relations
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/nest-foreign-key-relations.html'
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
        - name: Provide full resources where available
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-full-resources-where-available.html'
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
        - name: Provide full resources where available
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/provide-full-resources-where-available.html'
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
        - name: Use consistent path formats
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/use-consistent-path-formats.html'
        - name: Downcase paths and attributes
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/downcase-paths-and-attributes.html'
        - name: Minimize path nesting
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/requests/minimize-path-nesting.html'
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
        - name: Require Secure Connections
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/require-secure-connections.html'
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
        - name: Require Versioning in the Accepts Header
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/foundations/require-versioning-in-the-accepts-header.html'
        - name: Describe stability
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/artifacts/describe-stability.html'
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
      id: heroku-http-api-design-guide
      title: HTTP API Design Guide
      type: gitbook
      url: 'https://geemus.gitbooks.io/http-api-design/content/en/'
      company: Heroku
      companyLogoUrl: /media/logos/heroku.png
      companyUrl: 'https://devcenter.heroku.com/articles/platform-api-reference'
      date: 2016-07-05T00:00:00.000Z
      reviewDate: 2016-08-31T00:00:00.000Z
      _links:
        self:
          href: /design/guidelines/heroku-http-api-design-guide
        guidelineTopics:
          href: /design/guidelines/heroku-http-api-design-guide/topics
  _links:
    self:
      href: /design/guidelines/heroku-http-api-design-guide/topics
    guideline:
      href: /design/guidelines/heroku-http-api-design-guide
---