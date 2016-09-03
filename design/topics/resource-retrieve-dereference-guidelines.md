---
layout: topic
title: Dereference Relationships
permalink: /design/topics/resource-retrieve-dereference
data:
  items:
    - references:
        - name: REST Resources
          url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
          quote: Standard Query Parameters in URIs (expand)
        - name: REST Resources
          url: 'https://developer.atlassian.com/docs/atlassian-platform-common-components/rest-api-development/atlassian-rest-api-design-guidelines-version-1#AtlassianRESTAPIDesignGuidelinesversion1-RESTResources'
          quote: Title Expansion for Entities
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
        - name: null
          quote: 'If a service supports the fields parameter, then a value of @reference, @narrow, or @wide SHOULD...'
          url: null
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
        - name: Includind Related Resources
          url: 'https://github.com/cloudfoundry/cc-api-v3-style-guide#including-related-resources'
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
        name: Dereference Relationships
        description: How to load a resource and its linked resources in one call
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
        - name: Use Conventional Query Strings
          quote: embed — to expand embedded entities
          url: 'http://zalando.github.io/restful-api-guidelines/naming/Naming.html#could-use-conventional-query-strings'
        - name: Define useful resources
          url: 'http://zalando.github.io/restful-api-guidelines/resources/Resources.html#should-define-useful-resources'
        - name: Allow Optional Embedding of Sub-Resources
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#should-allow-optional-embedding-of-subresources'
        - name: Modify the Content-Type for Embedded Resources
          url: 'http://zalando.github.io/restful-api-guidelines/hyper-media/Hypermedia.html#must-modify-the-contenttype-for-embedded-resources'
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
      id: resource-retrieve-dereference
      name: Dereference Relationships
      description: How to load a resource and its linked resources in one call
      _links:
        self:
          href: /design/topics/resource-retrieve-dereference
        topicGuidelines:
          href: /design/topics/resource-retrieve-dereference/guidelines
  _links:
    self:
      href: /design/topics/resource-retrieve-dereference/guidelines
    topic:
      href: /design/topics/resource-retrieve-dereference
---