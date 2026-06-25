# to-duso

A TODO MVP web app built with [Duso](https://duso.rocks), a complete server runtime with zero dependencies and its own full featured web server and flexible nosql database.

Current version is 164 lines of code split into logical route handlers:

| File        | Description                                   |
|-------------|-----------------------------------------------|
| `server.du` | HTTP server setup and route definitions       |
| `index.du`  | Main page with session support and todo list  |
| `render.du` | Renders individual todo items as HTML         |
| `create.du` | Creates a new todo from form submission       |
| `edit.du`   | Shows inline edit form for a todo             |
| `update.du` | Saves an updated todo                         |
| `delete.du` | Deletes a todo                                |
| `toggle.du` | Toggles todo completion status                |

## Install Duso

Visit [duso.rocks/download](https://duso.rocks/download) to download Duso or install via Homebrew:

```bash
brew install duso-org/tap/duso
```

## Run the App

```bash
duso server.du
```

Open [http://localhost:8080](http://localhost:8080) to start using the todo app.

## Features

- REST API (create, read, update, delete, and complete todos)
- Sharable url-based multi-session support
- Interactive Web UI (thanks to HTMX)
- Persistent storage

## Tech Stack

- Backend: [Duso](https://duso.rocks)
- Frontend: [HTMX](https://htmx.org)

## Learn More

- [Duso Documentation](https://duso.rocks)
- [HTMX Documentation](https://htmx.org)
- [Blog Post](#) (coming soon)
- [Framework Comparison](https://duso.rocks/docs/docs/todo-comparison.html)

## License

[MIT](LICENSE)
