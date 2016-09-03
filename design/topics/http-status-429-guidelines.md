---
layout: topic
title: HTTP Status 429
permalink: /design/topics/http-status-429
data:
  items:
    - references:
        - name: Return appropriate status codes
          url: 'https://geemus.gitbooks.io/http-api-design/content/en/responses/return-appropriate-status-codes.html'
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
        - name: Client Side Error Codes
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#client-side-error-codes'
        - name: Use 429 with Headers for Rate Limits
          url: 'http://zalando.github.io/restful-api-guidelines/http/Http.html#must-use-429-with-headers-for-rate-limits'
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
      id: http-status-429
      name: HTTP Status 429
      description: When to use HTTP status 429
      _links:
        self:
          href: /design/topics/http-status-429
        topicGuidelines:
          href: /design/topics/http-status-429/guidelines
  _links:
    self:
      href: /design/topics/http-status-429/guidelines
    topic:
      href: /design/topics/http-status-429
---