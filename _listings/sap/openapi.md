swagger: "2.0"
x-collection-name: SAP
x-complete: 1
info:
  title: SAP Translation Hub
  description: to-provide-users-of-software-in-a-global-market-with-texts-in-their-own-language-translations-are-required--sap-translation-hub-enables-you-to-draw-on-saps-translation-experience-across-multiple-products-and-languages-to-propose-translations-for-short-texts-
  contact:
    name: SAP Translation Hub team
    email: translationhub@sap.com
  version: 1.0.0
host: sandbox.api.sap.com
basePath: /translationhub/api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations/{organizationId}/collaborationRooms:
    get:
      summary: Retrieves the collaboration rooms of an organization
      description: Retrieves the collaboration rooms where an organization is a collaboration
        party.
      operationId: retrieves-the-collaboration-rooms-where-an-organization-is-a-collaboration-party---
      x-api-path-slug: organizationsorganizationidcollaborationrooms-get
      parameters:
      - in: path
        name: organizationId
        description: The ID of an organization
      - in: query
        name: organizationIds
        description: The IDs of other organizations
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Collaboration
      - Rooms
      - Of
      - Organization
  /organizations/{organizationId}/collaborationRooms/owned:
    get:
      summary: Retrieves the collaboration rooms created by an organization
      description: Retrieves the collaboration rooms created and owned by an organization.
      operationId: retrieves-the-collaboration-rooms-created-and-owned-by-an-organization--
      x-api-path-slug: organizationsorganizationidcollaborationroomsowned-get
      parameters:
      - in: path
        name: organizationId
        description: The ID of the owner organization
      - in: query
        name: organizationIds
        description: The IDs of other organizations
      - in: query
        name: partId
        description: The ID of a part
      - in: query
        name: serviceType
        description: The type of service that a supplier organization provides during
          the collaboration
      - in: query
        name: status
        description: The status of a collaboration
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Collaboration
      - Rooms
      - Created
      - By
      - Organization
  /users/{userId}/collaborationRooms:
    get:
      summary: Retrieves a user's collaboration rooms
      description: "Retrieves the collaboration rooms where a user is a participant.
        \ \n- If the login user is not an organization admin, he or she can search
        only by his or her own user ID and retrieve the collaboration rooms where
        he or she is a participant.  \n- If the login user is an organization admin,
        he or she can search by the user ID of any user in the same organization."
      operationId: retrieves-the-collaboration-rooms-where-a-user-is-a-participant---if-the-login-user-is-not-an-organi
      x-api-path-slug: usersuseridcollaborationrooms-get
      parameters:
      - in: path
        name: userId
        description: The ID of a user
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Users
      - Collaboration
      - Rooms