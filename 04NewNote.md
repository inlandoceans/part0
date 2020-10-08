title New Note with HTTP POST

note over Browser
Submit button is clicked
end note
Browser->Server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note
note over Server: Timestamp
Server-->Browser: HTTP Status Code 302
Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/notes
Server-->Browser: HTML-Code
Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css
Server-->Browser: main.css
Browser->Server: https://studies.cs.helsinki.fi/exampleapp/main.js
Server-->Browser: main.js
note over Browser: 
JS Code
JSON request 
end note
Browser->Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json
Server->Browser: Status Code 200
