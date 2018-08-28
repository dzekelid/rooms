swagger: "2.0"
x-collection-name: TelAPI
x-complete: 1
info:
  title: TelAPI
  description: telapi-is-a-rest-api--what-that-means-for-you-is-that-interacting-with-telapi-to-perform-all-of-your-telephony-needs-is-almost-as-simple-as-visiting-a-website--deeper-knowledge-regarding-rest-is-useful-when-developing-with-telapi-but-definitely-not-required--we-aim-to-provide-all-of-the-information-needed-for-working-with-our-rest-api-throughout-its-documentation-provided-here-so-even-if-you-are-new-to-rest-telapi-will-still-be-a-pleasure-to-use-
  termsOfService: http://www.telapi.com/legal/tos
  version: v2
host: api.telapi.com
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/hotel/v0/hotels/{hotelId}/rooms:
    get:
      summary: Get a list of rooms using the provided filtering and pagination criteria.
      description: "Find all rooms for the hotel that match the specified filter criteria.
        The filtering will be done based on the current state of\r\n            the
        rooms."
      operationId: Rooms_GetRooms
      x-api-path-slug: apihotelv0hotelshotelidrooms-get
      parameters:
      - in: query
        name: amenities
        description: Return result only for rooms having all of the given amenities
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: query
        name: conditions
        description: Return results only for rooms that have the given room condition
          status
      - in: path
        name: hotelId
        description: The hotel you are trying to find rooms for
      - in: query
        name: inlinecount
        description: Return total number of items for a given filter criteria
      - in: query
        name: locations
        description: Return result only for rooms having at least one of the specified
          locations
      - in: query
        name: maintenances
        description: Return results only for rooms that have the given maintenance
          status
      - in: query
        name: occupancy
        description: Return results only for rooms that have the given frontdesk ocuppancy
          status
      - in: query
        name: roomTypes
        description: Return result only for rooms for the given room types
      - in: query
        name: skip
        description: Amount of items to skip
      - in: query
        name: top
        description: Amount of items to select
      - in: query
        name: views
        description: Return result only for rooms having at least one of the specified
          views
      responses:
        200:
          description: OK
      tags:
      - Rooms
      - Using
      - Provided
      - Filtering
      - Pagination
      - Criteria
  /api/hotel/v0/hotels/{hotelId}/rooms/$count:
    get:
      summary: Get the count of all rooms in the hotel matching the given filter criteria.
      description: Get the count of all rooms in the hotel matching the given filter
        criteria..
      operationId: Rooms_GetRoomsCount
      x-api-path-slug: apihotelv0hotelshotelidroomscount-get
      parameters:
      - in: query
        name: amenities
        description: Return result only for rooms having all of the given amenities
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: query
        name: conditions
        description: Return results only for rooms that have the given room condition
          status
      - in: path
        name: hotelId
        description: The hotel you are counting the rooms for
      - in: query
        name: locations
        description: Return result only for rooms having at least one of the specified
          locations
      - in: query
        name: maintenances
        description: Return results only for rooms that have the given maintenance
          status
      - in: query
        name: occupancy
        description: Return results only for rooms that have the given frontdesk ocuppancy
          status
      - in: query
        name: roomTypes
        description: Return result only for rooms for the given room types
      - in: query
        name: views
        description: Return result only for rooms having at least one of the specified
          views
      responses:
        200:
          description: OK
      tags:
      - Count
      - Of
      - ""
      - Rooms
      - In
      - Hotel
      - Matching
      - Given
      - Filter
      - Criteria
  /api/hotel/v0/hotels/{hotelId}/rooms/available:
    get:
      summary: Request available rooms using a given criteria.
      description: Request available rooms using a given criteria..
      operationId: Rooms_GetAvailableRooms
      x-api-path-slug: apihotelv0hotelshotelidroomsavailable-get
      parameters:
      - in: query
        name: adults
        description: Specifies number of adults the returned rooms will have to be
          able to house
      - in: query
        name: amenities
        description: Return result only for rooms having all of the given amenities
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: query
        name: from
        description: Rooms returned will not be assigned to a reservation or be under
          maintenance between this date            and the specified to date
      - in: path
        name: hotelId
        description: The hotel you are looking for available rooms
      - in: query
        name: includeOutOfService
        description: Should rooms that are set OutOfService in the defined time period
          be returned as available
      - in: query
        name: inlinecount
        description: Return total number of items for a given filter criteria
      - in: query
        name: locations
        description: Return result only for rooms having at least one of the specified
          locations
      - in: query
        name: roomTypes
        description: Return result only for rooms for the given room types
      - in: query
        name: skip
        description: Amount of items to skip
      - in: query
        name: to
        description: Rooms returned will not be assigned to a reservation or be under
          maintenance between the specified            from date and this date
      - in: query
        name: top
        description: Amount of items to select
      - in: query
        name: views
        description: Return result only for rooms having at least one of the specified
          views
      responses:
        200:
          description: OK
      tags:
      - Request
      - Available
      - Rooms
      - Using
      - Given
      - Criteria