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
server->>browser HTML Document
desactivate server

browser->>server GET https://studies.cs.helsinki.fi/exampleapp/spa 
activate server
server->>browser HTML Document
desactivate server 
