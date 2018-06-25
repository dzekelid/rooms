---
name: TelAPI
x-slug: telapi
description: Zang offers business communications tools & voice app development platforms
  that bring innovation and ease to unified communications & collaboration solutions.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
x-kinRank: "9"
x-alexaRank: "1071695"
tags: Rooms
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rooms/master/_listings/telapi/apis.md
specificationVersion: "0.14"
apis:
- name: hetras Hotel API Version 0 Get a list of rooms using the provided filtering
    and pagination criteria.
  x-api-slug: hetras-hotel-api-version-0
  description: "Find all rooms for the hotel that match the specified filter criteria.
    The filtering will be done based on the current state of\r\n            the rooms."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
  humanURL: http://www.telapi.com
  baseURL: https://api.hetras-certification.net////api/hotel/v0/hotels/{hotelId}/rooms
  tags: Rooms,Using,Provided,Filtering,Pagination,Criteria
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rooms/master/_listings/telapi/apihotelv0hotelshotelidrooms-get-openapi.md
- name: hetras Hotel API Version 0 Get the count of all rooms in the hotel matching
    the given filter criteria.
  x-api-slug: hetras-hotel-api-version-0
  description: Get the count of all rooms in the hotel matching the given filter criteria..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
  humanURL: http://www.telapi.com
  baseURL: https://api.hetras-certification.net////api/hotel/v0/hotels/{hotelId}/rooms/$count
  tags: Count,Of,,Rooms,In,Hotel,Matching,Given,Filter,Criteria
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rooms/master/_listings/telapi/apihotelv0hotelshotelidroomscount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rooms/master/_listings/telapi/apihotelv0hotelshotelidroomscount-get-openapi.md
- name: hetras Hotel API Version 0 Request available rooms using a given criteria.
  x-api-slug: hetras-hotel-api-version-0
  description: Request available rooms using a given criteria..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
  humanURL: http://www.telapi.com
  baseURL: https://api.hetras-certification.net////api/hotel/v0/hotels/{hotelId}/rooms/available
  tags: Request,Available,Rooms,Using,Given,Criteria
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rooms/master/_listings/telapi/apihotelv0hotelshotelidroomsavailable-get-openapi.md
- name: hetras Hotel API Version 0
  x-api-slug: hetras-hotel-api-version-0
  description: Zang offers business communications tools & voice app development platforms
    that bring innovation and ease to unified communications & collaboration solutions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
  humanURL: http://www.telapi.com
  baseURL: https://api.hetras-certification.net//
  tags: Rooms
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rooms/master/_listings/telapi/openapi.md
x-common:
- type: x-base
  url: https://api.telapi.com
- type: x-blog
  url: http://www.TelAPI.com/blog/
- type: x-blog-rss
  url: http://www.telapi.com/blog/feed/
- type: x-contact-form
  url: http://www.telapi.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/telapi
- type: x-crunchbase
  url: https://crunchbase.com/organization/zang-io
- type: x-developer
  url: http://www.telapi.com/docs/
- type: x-email
  url: support@telapi.com
- type: x-github
  url: https://github.com/TelAPI
- type: x-pricing
  url: http://www.telapi.com/pricing
- type: x-privacy
  url: https://www.telapi.com/legal/privacy-policy
- type: x-selfservice-registration
  url: https://www.telapi.com/signup
- type: x-status
  url: http://status.telapi.com/
- type: x-terms-of-service
  url: https://www.telapi.com/legal/tos
- type: x-twitter
  url: https://twitter.com/TelAPI
- type: x-twitter
  url: https://twitter.com/Zang_io
- type: x-website
  url: http://www.telapi.com
- type: x-website
  url: http://telapi.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---