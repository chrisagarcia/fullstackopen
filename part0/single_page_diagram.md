
client->>server: GET https://studies.cs.helsinki.fi/exampleapp/spa
server->>client: HTML Document

client: GET https://studies.cs.helsinki.fi/exampleapp/main.css
server->>client: CSS File

client: GET https://studies.cs.helsinki.fi/exampleapp/spa.js
server->>client: JavaScript File

client: GET https://studies.cs.helsinki.fi/exampleapp/data.json
server->>client: JSON File
