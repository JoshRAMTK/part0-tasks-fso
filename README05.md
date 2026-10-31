mermaid 
sequenceDiagram 

browser->>server GET https://studies.cs.helsinki.fi/exampleapp/spa 
activate server
server->>browser HTML Document
desactivate server 


browser->>server GET https://studies.cs.helsinki.fi/exampleapp/main.css
activate server
server->>browser CSS Document
desactivate server


browser->>server GET https://studies.cs.helsinki.fi/exampleapp/spa.js
activate server
server->>browser JavaScript file
desactivate server 


browser->>server GET https://studies.cs.helsinki.fi/exampleapp/data.json
activate server
server->>browser
[{ "content": "Note example", "date": "2025-03-12" }, ... ] 
[{ "content": "Another note example", "date": "2022-04.23" }, ... ] 
desactivate server

#I think its ok this mermaid
