´´´mermaid
sequenceDiagram
participant browser
participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: [{ "content": "exercise 0.6", "date": "2024-5-28" }, ... ]
    deactivate server

´´´
