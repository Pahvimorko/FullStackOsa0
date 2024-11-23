
sequenceDiagram
    Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/new_note
    Server-->>Browser: Status Code: 302
    Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/notes
    Server-->>Browser: HTML document
    Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/main.css
    Server-->>Browser: the css file
    Browser->>Server: https://studies.cs.helsinki.fi/exampleapp/main.js
    Server-->>Browser: the JavaScript file
    Browser->>Server: GET https://studies.cs.helsinki.fi/exampleapp/data.json
    Server-->>Browser: the Json data


   


