---
swagger: "2.0"
x-collection-name: SAP
x-complete: 0
info:
  title: SAP Manufacturing Network Customer APIs Retrieves a user's collaboration
    rooms
  description: "Retrieves the collaboration rooms where a user is a participant.  \n-
    If the login user is not an organization admin, he or she can search only by his
    or her own user ID and retrieve the collaboration rooms where he or she is a participant.
    \ \n- If the login user is an organization admin, he or she can search by the
    user ID of any user in the same organization."
  version: 1.0.0
host: hostname
basePath: /dim/api
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
      description: "Retrieves the collaboration rooms where the login user's organization
        is a collaboration party.   \n- If the login user is not an organization admin,
        only the collaboration rooms where the login user is a participant are retrieved.
        \  \n- If the login user is an organization admin, all the collaboration rooms
        where the login user's organization is a collaboration party are retrieved.
        The login user may not be part of the collaborations."
      operationId: retrieves-the-collaboration-rooms-where-the-login-users-organization-is-a-collaboration-party----if-
      x-api-path-slug: organizationsorganizationidcollaborationrooms-get
      parameters:
      - in: path
        name: organizationId
        description: The ID of the login users organization
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
      description: "Retrieves the collaboration rooms created and owned by an organization.
        \ \n- If the login user is not an organization admin, only the collaboration
        rooms where the login user is a participant are retrieved.  \n- If the login
        user is an organization admin, all the collaboration rooms owned by the login
        user's organization are retrieved."
      operationId: retrieves-the-collaboration-rooms-created-and-owned-by-an-organization---if-the-login-user-is-not-an
      x-api-path-slug: organizationsorganizationidcollaborationroomsowned-get
      parameters:
      - in: path
        name: organizationId
        description: The ID of the login users organization
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---