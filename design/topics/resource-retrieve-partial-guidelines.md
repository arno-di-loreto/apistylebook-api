---
layout: topic
title: Retrieve resource partially
permalink: /design/topics/resource-retrieve-partial
data:
  items:
    - references:
        - name: 3.6.3.6 Services MAY support partial retrieval of resource state
          quote: RFC-3986
          url: 'https://github.com/CiscoDevNet/api-design-guide#363-get'
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
        - name: Requesting Partiel Resources
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#requesting-partial-resources'
        - name: Nested Resources
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#nested-resources'
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
        guideline:
          href: /design/guidelines/cloud-foundy-cloud-controller-api-style-guide
    - references:
        - name: Field selection
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/filtering-sorting-field-selection-and-paging/filtering-sorting-field-selection-and-paging.md#field-selection'
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
        - name: Standard request headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#75-standard-request-headers'
          quote: 'Prefer return=minimal, return=representation'
        - name: Standard response headers
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#76-standard-response-headers'
          quote: Preference-Applied
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
        - name: Use Conventional Query Strings
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
          quote: fields — to retrieve a subset of fields
        - name: Define useful resources
          url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#should-define-useful-resources'
        - name: Support Filtering of Resource Fields
          url: 'http://zalando.github.io/restful-api-guidelines/performance/Performance.html#should-support-filtering-of-resource-fields'
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
      id: resource-retrieve-partial
      name: Retrieve resource partially
      description: How to retrieve partially a resource
      _links:
        self:
          href: /design/topics/resource-retrieve-partial
        topicGuidelines:
          href: /design/topics/resource-retrieve-partial/guidelines
  _links:
    self:
      href: /design/topics/resource-retrieve-partial/guidelines
    topic:
      href: /design/topics/resource-retrieve-partial
---