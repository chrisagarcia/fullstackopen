
... starting from form submission


client pushes new note to local memory
client re-renders the notes including new note

client->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
server->>client: 201 Created