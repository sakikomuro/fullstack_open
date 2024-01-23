```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa, {content: "yummy", date: "2024-01-23T08:26:59.790Z"}
    activate server
    server-->>browser: 201 Created {"message":"note created"}
    deactivate server

```
