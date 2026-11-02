mermaid sequenceDiagram

browser->>server GET https://studies.cs.helsinki.fi/exampleapp/spa activate server server->>browser HTML Document desactivate server

browser->>server GET https://studies.cs.helsinki.fi/exampleapp/main.css activate server server->>browser CSS Document desactivate server

browser->>server GET https://studies.cs.helsinki.fi/exampleapp/spa.js activate server server->>browser JavaScript file desactivate server

browser->>server GET https://studies.cs.helsinki.fi/exampleapp/data.json activate server server->>browser [{ "content": "Note example", "date": "2025-03-12" }, ... ] [{ "content": "Another note example", "date": "2022-04.23" }, ... ] desactivate server

browser->>server POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa activate server server->>browser [{ "content": "created note", "date": "2026-10-31" }, ... ] desactivate server

#Same mermaaid as the readme05 but another request so I copied and pasted it 
