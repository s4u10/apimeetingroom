
Meeting room manager - Back-End

    Used:
    Spring Web
    Spring Data JPA
    H2 Database
    Java 11
    Maven
    Heroku

----Endpoints created in the API---

    create meeting room POST - /api/v1/rooms 
    List all rooms GET - /api/v1/rooms 
    Search for a room by Id GET - /api/v1/rooms/{id} 
    Update a room by Id PUT - /api/v1/rooms/{id} 
    Delete a room by id DELETE - /api/v1/rooms/{Id} 

Link Heroku

https://app-apimeetingroom.herokuapp.com/api/v1/rooms


JSON templet:

{
    "name": "Test JSON",
    "date": "25/01/2022",
    "startHour": "20hs",
    "endHour": "21hs" 
}
