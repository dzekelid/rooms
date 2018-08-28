---
name: SAP
x-slug: sap
description: Get software and technology solutions from SAP, the leader in business
  applications.  Run simple with the best in cloud, analytics, mobile and IT solutions.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28252-www-sap-com.jpg
x-kinRank: "8"
x-alexaRank: "1965"
tags: Rooms
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rooms/master/_listings/sap/apis.md
specificationVersion: "0.14"
apis:
- name: Manufacturing Network Customer APIs - Retrieves the collaboration rooms of
    an organization
  x-api-slug: organizationsorganizationidcollaborationrooms-get
  description: "Retrieves the collaboration rooms where the login user's organization
    is a collaboration party.   \n- If the login user is not an organization admin,
    only the collaboration rooms where the login user is a participant are retrieved.
    \  \n- If the login user is an organization admin, all the collaboration rooms
    where the login user's organization is a collaboration party are retrieved. The
    login user may not be part of the collaborations."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28252-www-sap-com.jpg
  humanURL: https://www.sap.com/index.html
  baseURL: https://hostname//dim/api
  tags: SaaS, Technology, Enterprise, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rooms/master/_listings/sap/organizationsorganizationidcollaborationrooms-get-openapi.md
- name: Manufacturing Network Customer APIs - Retrieves the collaboration rooms created
    by an organization
  x-api-slug: organizationsorganizationidcollaborationroomsowned-get
  description: "Retrieves the collaboration rooms created and owned by an organization.
    \ \n- If the login user is not an organization admin, only the collaboration rooms
    where the login user is a participant are retrieved.  \n- If the login user is
    an organization admin, all the collaboration rooms owned by the login user's organization
    are retrieved."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28252-www-sap-com.jpg
  humanURL: https://www.sap.com/index.html
  baseURL: https://hostname//dim/api
  tags: SaaS, Technology, Enterprise, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rooms/master/_listings/sap/organizationsorganizationidcollaborationroomsowned-get-openapi.md
- name: Manufacturing Network Customer APIs - Retrieves a user's collaboration rooms
  x-api-slug: usersuseridcollaborationrooms-get
  description: "Retrieves the collaboration rooms where a user is a participant.  \n-
    If the login user is not an organization admin, he or she can search only by his
    or her own user ID and retrieve the collaboration rooms where he or she is a participant.
    \ \n- If the login user is an organization admin, he or she can search by the
    user ID of any user in the same organization."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28252-www-sap-com.jpg
  humanURL: https://www.sap.com/index.html
  baseURL: https://hostname//dim/api
  tags: SaaS, Technology, Enterprise, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rooms/master/_listings/sap/usersuseridcollaborationrooms-get-openapi.md
- name: Manufacturing Network Partner APIs - Retrieves the collaboration rooms of
    an organization
  x-api-slug: organizationsorganizationidcollaborationrooms-get
  description: Retrieves the collaboration rooms where an organization is a collaboration
    party.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28252-www-sap-com.jpg
  humanURL: https://www.sap.com/index.html
  baseURL: https://hostname//dim/api
  tags: SaaS, Technology, Enterprise, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rooms/master/_listings/sap/organizationsorganizationidcollaborationrooms-get-openapi.md
- name: Manufacturing Network Partner APIs - Retrieves the collaboration rooms created
    by an organization
  x-api-slug: organizationsorganizationidcollaborationroomsowned-get
  description: Retrieves the collaboration rooms created and owned by an organization.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28252-www-sap-com.jpg
  humanURL: https://www.sap.com/index.html
  baseURL: https://hostname//dim/api
  tags: SaaS, Technology, Enterprise, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rooms/master/_listings/sap/organizationsorganizationidcollaborationroomsowned-get-openapi.md
x-common:
- type: x-website
  url: https://www.sap.com/index.html
- type: x-api-gallery
  url: http://santander.bank.api.gallery.streamdata.io
- type: x-api-stack
  url: http://sap.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/sap-canada
- type: x-developer
  url: https://api.sap.com/
- type: x-github
  url: https://github.com/sap
- type: x-twitter
  url: https://twitter.com/SAP
- type: x-website
  url: https://www.sap.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---