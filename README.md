## Skill Street Note Node APIs Documentation

1. Create a New Note
   
Endpoint: /api/notes

Method: POST

Description: Create a new note with a specified title and content.

Request Body:

title (string): Title of the note (required).
content (string): Content of the note (required).

Example:

POST http://localhost:3000/api/notes
Content-Type: application/json

  {
  "title": "Meeting Notes",
  "content": "Discuss project updates and plan for the next sprint."
  }

2. Retrieve All Notes
   
  Endpoint: /api/notes
  
  Method: GET
  
  Description: Retrieve all notes.
  
  Example:

    GET http://localhost:3000/api/notes

4. Retrieve a Single Note by ID
   
   Endpoint: /api/notes/:id
   
  Method: GET
  
  Description: Retrieve a single note by its unique identifier (ID).

  Example:

    GET http://localhost:3000/api/notes/123456789

5. Update a Note
   
  Endpoint: /api/notes/:id
  
  Method: PUT
  
  Description: Update an existing note by its ID.
  
  Request Body:
  
  title (string): Updated title of the note (required).
  
  content (string): Updated content of the note (required).
  
  Example:

    PUT http://localhost:3000/api/notes/123456789
    
  Content-Type: application/json

  {
  "title": "Updated Meeting Notes",
  "content": "Reviewed action items and set priorities for the next week."
  }

5. Delete a Note
   
  Endpoint: /api/notes/:id

  Method: DELETE
  
  Description: Delete a note by its ID.
  
  Example:
DELETE http://localhost:3000/api/notes/123456789


    DELETE http://localhost:3000/api/notes/123456789





