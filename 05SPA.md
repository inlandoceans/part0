title SPA

browser->server: https://studies.cs.helsinki.fi/exampleapp/spa
server-->browser: HTML
browser->server: https://studies.cs.helsinki.fi/exampleapp/main.css
server-->browser: main.css
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa.js
server-->browser: spa.js

note over browser:
JS -> JSON
end note

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json
server-->browser: return note objects

