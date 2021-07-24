    When client register with username and password, Backend maintain a record in database.

    When client tries to login, backend will create a random sessonid and store it in database and also send the same to client. Stored in client browser cookies.

    If client makes subsequent requests with this session id, backend can identify the client using session id else client needs to login again.

    When client logout, this session id will be set to null in database.
    
     


