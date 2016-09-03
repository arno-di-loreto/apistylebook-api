---
layout: topic
title: HTTP Headers
permalink: /design/topics/http-headers
data:
  items:
    - references:
        - name: REST Resources
          url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
          quote: Entities SHOULD be served with an ETag header.
        - name: Caching
          url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-Caching'
          quote: 'ETag, If-None-Match'
      _embedded:
        guideline:
          id: atlassian-rest-api-design-guidelines-version-1
          title: Atlassian REST API Design Guidelines version 1
          type: website
          url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1'
          company: Atlassian
          companyLogoUrl: /media/logos/atlassian.png
          companyUrl: 'https://developer.atlassian.com/'
          date: 2016-01-22T00:00:00.000Z
          reviewDate: 2016-09-01T00:00:00.000Z
          _links:
            self:
              href: /design/guidelines/atlassian-rest-api-design-guidelines-version-1
            guidelineTopics:
              href: /design/guidelines/atlassian-rest-api-design-guidelines-version-1/topics
      _links:
        guideline:
          href: /design/guidelines/atlassian-rest-api-design-guidelines-version-1
    - references:
        - name: Detectability (Deprecation Policy)
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Detectability'
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
        guideline:
          href: /design/guidelines/atlassian-rest-api-policy
    - references:
        - name: 3.5 HTTP Headers
          url: 'https://github.com/CiscoDevNet/api-design-guide#351-standard-headers'
        - name: 3.6.1 POST
          quote: Location header
          url: 'https://github.com/CiscoDevNet/api-design-guide#361-post'
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
        guideline:
          href: /design/guidelines/cisco-api-design-guide
    - references:
        - name: Expires HTTP Header
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#expires-http-header'
        - name: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#cache-control-header'
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#cache-control-header'
        - name: ETag
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/caching/caching.md#etag'
      _embedded:
        guideline:
          id: haufe-api-styleguide
          title: Haufe API style guide
          type: github
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/readme.md'
          company: Haufe
          companyLogoUrl: /media/logos/haufe.png
          companyUrl: 'http://dev.haufe.com/'
          date: 2015-01-15T00:00:00.000Z
          reviewDate: 2016-08-31T00:00:00.000Z
          _links:
            self:
              href: /design/guidelines/haufe-api-styleguide
            guidelineTopics:
              href: /design/guidelines/haufe-api-styleguide/topics
      _links:
        guideline:
          href: /design/guidelines/haufe-api-styleguide
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
        guideline:
          href: /design/guidelines/heroku-http-api-design-guide
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
        guideline:
          href: /design/guidelines/microsoft-rest-api-guidelines
    - references:
        - name: Link Headers
          url: 'http://restful-api-design.readthedocs.io/en/latest/methods.html#link-headers'
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
        guideline:
          href: /design/guidelines/redhat-thoughts-on-restful-api-design
    - references:
        - name: General guidelines for RESTful URLs
          quote: URL v. header
          url: 'https://github.com/WhiteHouse/api-standards/blob/master/README.md#general-guidelines-for-restful-urls'
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
        guideline:
          href: /design/guidelines/white-house-web-api-standards
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
        guideline:
          href: /design/guidelines/zalando-restful-api-guidelines
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
    self:
      href: /design/topics/http-headers/guidelines
    topic:
      href: /design/topics/http-headers
---