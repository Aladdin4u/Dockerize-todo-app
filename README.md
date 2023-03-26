## Dockerize todo app
A simple todo list app running on Node.js.

## Usage

### Prerequisites

- Docker Desktop.
- Node and Node Package Manager ([npm](https://www.npmjs.com/get-npm)).
- Familiarity with your computer's terminal/command line interface.

### Building Locally

The easiest way to see this project in action is to build your Worker locally and copy/paste it into Cloudflare's UI:

- Clone this repo: `git clone <repo https address>`
- Build container image: `docker build -t todolist .`
- Runnning application: `docker compose up -d`
- opening web browser: `http://localhost:3000`
- view application logs: `docker compose logs -f`
- stop application: `docker compose down`