# QueryLens

An AI-powered chatbot interface for querying company information at the NVIDIA AI Summit. Built as a static web page with an embedded DigitalOcean AI agent chatbot widget, containerized with Nginx for deployment.

## Features

- **AI Chatbot Widget** -- Embedded DigitalOcean AI agent for natural language queries
- **Company Search** -- Find details about companies participating in the NVIDIA AI Summit
- **Natural Language Interface** -- Ask questions like "What does XCube Labs do?" or "List companies in the Energy sector"
- **Containerized Deployment** -- Nginx-based Docker image for easy hosting

## Tech Stack

- **Frontend:** HTML, CSS
- **Chatbot:** DigitalOcean AI Agent (embedded widget)
- **Web Server:** Nginx (Alpine)
- **Containerization:** Docker

## Setup / Installation

### Local

```bash
git clone https://github.com/bnarasimha21/query-lens.git
cd query-lens
open index.html
```

### Docker

```bash
docker build -t query-lens .
docker run -p 80:80 query-lens
```

Then open `http://localhost` in your browser.

## Usage

1. Open the page in your browser
2. Click the chat icon in the bottom-right corner
3. Type your question about participating companies (e.g., "How many companies are based out of Delhi?")
4. Receive instant AI-powered answers with follow-up support

### Example Queries

- "What does XCube Labs do?"
- "How many companies are based out of Delhi?"
- "List the companies which are in Energy sector"

## License

MIT
