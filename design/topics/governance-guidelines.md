---
layout: topic
title: Governance
permalink: /design/topics/governance
data:
  items:
    - references:
        - name: Using these Guidelines
          url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-UsingtheseGuidelines'
          quote: We strongly recommend that someone who is familiar with these guidelines should review your REST API code
        - name: Version Control for APIs
          url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-VersionControlforAPIs'
          quote: When to Change the Version
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
        - name: Compatibility policy
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Compatibilitypolicy'
        - name: Deprecation policy
          url: 'https://developer.atlassian.com/display/HOME/Atlassian+REST+API+policy#AtlassianRESTAPIpolicy-Deprecationpolicy'
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
        - name: Register your API
          url: 'https://apiguide.readthedocs.io/en/latest/build_and_publish/advertise.html'
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
        guideline:
          href: /design/guidelines/ausdto-api-design-guide
    - references:
        - name: API Modelling and Design Process
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-process/api-design-process.md#api-modelling-and-design-process'
        - name: API Design Review Process
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/api-design-review-process/api-design-review-process.md'
        - name: Message Schema and Postel's Law
          url: 'https://github.com/Haufe-Lexware/api-style-guide/blob/master/message-schema/message-schema.md'
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
        - name: Interpreting The Guidelines
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#4-interpreting-the-guidelines'
        - name: When to version
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#122-when-to-version'
        - name: Definition of a breaking change
          url: 'https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md#123-definition-of-a-breaking-change'
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
        - name: API First
          url: 'http://zalando.github.io/restful-api-guidelines/general-guidelines/GeneralGuidelines.html#must-api-first-define-apis-using-openapi'
        - name: Deprecation
          url: 'http://zalando.github.io/restful-api-guidelines/deprecation/Deprecation.html'
        - name: API Discovery
          url: 'http://zalando.github.io/restful-api-guidelines/api-discovery/ApiDiscovery.html'
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
      id: governance
      name: Governance
      description: 'How to ensure API governance (advertise, consistency, ...)'
      _links:
        self:
          href: /design/topics/governance
        topicGuidelines:
          href: /design/topics/governance/guidelines
  _links:
    self:
      href: /design/topics/governance/guidelines
    topic:
      href: /design/topics/governance
---