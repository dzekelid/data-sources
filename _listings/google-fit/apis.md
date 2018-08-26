---
name: Google Fit
x-slug: google-fit
description: Google Fit is an open ecosystem that allows developers to upload fitness
  data to a central repository where users can access their data from different devices
  and apps in one location. Fitness apps can store data from any wearable or sensor.
  Fitness apps can access data created by any app. Users fitness data is persisted
  when they upgrade their fitness devices.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fit.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Data Sources
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data-sources/master/_listings/google-fit/apis.md
specificationVersion: "0.14"
apis:
- name: Fitness - Get Data Sources
  x-api-slug: useriddatasources-get
  description: Lists all data sources that are visible to the developer, using the
    OAuth scopes provided. The list is not exhaustive; the user may have private data
    sources that are only visible to other developers, or calls using other scopes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fit.jpg
  humanURL: https://developers.google.com/fit/overview
  baseURL: ://www.googleapis.com//fitness/v1/users
  tags: Fitness, Wearables, Google APIs, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data-sources/master/_listings/google-fit/useriddatasources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data-sources/master/_listings/google-fit/useriddatasources-get-openapi.md
- name: Fitness - Delete Data Source
  x-api-slug: useriddatasourcesdatasourceid-delete
  description: Deletes the specified data source. The request will fail if the data
    source contains any data points.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fit.jpg
  humanURL: https://developers.google.com/fit/overview
  baseURL: ://www.googleapis.com//fitness/v1/users
  tags: Fitness, Wearables, Google APIs, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data-sources/master/_listings/google-fit/useriddatasourcesdatasourceid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data-sources/master/_listings/google-fit/useriddatasourcesdatasourceid-delete-openapi.md
- name: Fitness - Get Data Source
  x-api-slug: useriddatasourcesdatasourceid-get
  description: Returns the specified data source.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fit.jpg
  humanURL: https://developers.google.com/fit/overview
  baseURL: ://www.googleapis.com//fitness/v1/users
  tags: Fitness, Wearables, Google APIs, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data-sources/master/_listings/google-fit/useriddatasourcesdatasourceid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data-sources/master/_listings/google-fit/useriddatasourcesdatasourceid-get-openapi.md
- name: Fitness - Get Data Sources
  x-api-slug: useriddatasources-get
  description: Lists all data sources that are visible to the developer, using the
    OAuth scopes provided. The list is not exhaustive; the user may have private data
    sources that are only visible to other developers, or calls using other scopes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fit.jpg
  humanURL: https://developers.google.com/fit/overview
  baseURL: ://www.googleapis.com//fitness/v1/users
  tags: Fitness, Wearables, Google APIs, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data-sources/master/_listings/google-fit/useriddatasources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data-sources/master/_listings/google-fit/useriddatasources-get-openapi.md
- name: Fitness - Delete Data Source
  x-api-slug: useriddatasourcesdatasourceid-delete
  description: Deletes the specified data source. The request will fail if the data
    source contains any data points.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fit.jpg
  humanURL: https://developers.google.com/fit/overview
  baseURL: ://www.googleapis.com//fitness/v1/users
  tags: Fitness, Wearables, Google APIs, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data-sources/master/_listings/google-fit/useriddatasourcesdatasourceid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data-sources/master/_listings/google-fit/useriddatasourcesdatasourceid-delete-openapi.md
- name: Fitness - Get Data Source
  x-api-slug: useriddatasourcesdatasourceid-get
  description: Returns the specified data source.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fit.jpg
  humanURL: https://developers.google.com/fit/overview
  baseURL: ://www.googleapis.com//fitness/v1/users
  tags: Fitness, Wearables, Google APIs, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data-sources/master/_listings/google-fit/useriddatasourcesdatasourceid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data-sources/master/_listings/google-fit/useriddatasourcesdatasourceid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.drive.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.fit.stack.network
- type: x-authentication
  url: https://developers.google.com/fit/android/get-api-key
- type: x-getting-started
  url: https://developers.google.com/fit/rest/v1/get-started
- type: x-website
  url: https://developers.google.com/fit/overview
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---