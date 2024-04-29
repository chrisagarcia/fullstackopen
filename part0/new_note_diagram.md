
... starting from from submission

browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/notes/example_app/new_note
server-side code pushes payload object to an array
server->>browser: 302 redirects browser to new URL

browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/notes
server-->>browser: HTML document

browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/main.css
server-->>browser: the css file

browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/main.js
server-->>browser: the JavaScript file

browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/data.json
server-->>browser: [{ "content": "HTML is easy", "date": "2023-1-1" }, ... ]

client js renders notes again with new data