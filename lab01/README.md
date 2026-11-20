# 953261 Lab 1 — First Node.js Server

| | |
|---|---|
| **Name** |May Chan Ko |
| **Nickname** | Mika|
| **Student ID** | 692115506 |
| **Section** | 701 |

## How to run

```bash
cd lab01
npm start
```

Then open <http://localhost:3000> and <http://localhost:3000/api/me>.

## What I learned today

_Write 2–3 sentences in your own words: what happens between typing a URL and seeing the page?_

        The URL is parsed and the page is found using DNS look up to get to the correct server. The client sends a HTTP Request and the server will respond with the appropriate status and body. Then, the page is rendered.

## AI-use statement

_Did you use an AI tool in this lab? If yes, which one and for what (e.g., "ChatGPT to explain a Git error message"). If no, write "No AI tools used."_

     I used Copilot in order to figure out how to write the code for if the HTTP request is 200 or 404, and what content will be sent back. I used Copilot to help explain exactly what those codes used mean e.g. "res.writeHead(200,{"Content-Type"...})..."