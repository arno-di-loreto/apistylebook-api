---
layout: guideline
title: Atlassian REST API Policy
permalink: /design/guidelines/atlassian-rest-api-policy
data:
  items:
    - references:
        - name: Resource/rate limits and paging
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Resource/ratelimitsandpaging'
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
        - name: Compatibility policy
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Compatibilitypolicy'
        - name: Structured representations (application/json)
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Structuredrepresentations(application/json)'
        - name: Forward compatibility
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Forwardcompatibility'
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
        - name: Deprecation policy
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Deprecationpolicy'
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
        - name: Compatibility policy
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Compatibilitypolicy'
        - name: Deprecation policy
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Deprecationpolicy'
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
        - name: Detectability (Deprecation Policy)
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Detectability'
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
        - name: Resource/rate limits and paging
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Resource/ratelimitsandpaging'
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
        - name: Stable URIs
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-StableURIs'
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
        - name: Compatibility policy
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Compatibilitypolicy'
        - name: Backwards compatibility
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Backwardscompatibility'
        - name: Structured representations (application/json)
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Structuredrepresentations(application/json)'
        - name: API versioning
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-APIversioning'
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
      id: atlassian-rest-api-policy
      title: Atlassian REST API Policy
      type: website
      url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy'
      company: Atlassian
      companyLogoUrl: /media/logos/atlassian.png
      companyUrl: 'https://developer.atlassian.com/'
      date: 2015-01-15T00:00:00.000Z
      reviewDate: 2016-09-01T00:00:00.000Z
      _links:
        self:
          href: /design/guidelines/atlassian-rest-api-policy
        guidelineTopics:
          href: /design/guidelines/atlassian-rest-api-policy/topics
  _links:
    self:
      href: /design/guidelines/atlassian-rest-api-policy/topics
    guideline:
      href: /design/guidelines/atlassian-rest-api-policy
---