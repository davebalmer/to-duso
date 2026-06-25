# to-duso

A minimal todo MVP built with [Duso](https://duso.rocks) — a complete server runtime with zero dependencies.

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

- REST API (create, read, update, delete todos)
- Session support (each session has its own todos)
- Persistent storage with WAL
- Web UI
- Zero dependencies
- Single 10MB binary
- Built-in web server and datastore

## Learn More

- [Duso Documentation](https://duso.rocks)
- [Blog Post](#) (coming soon)
- [Framework Comparison](#) (coming soon)

## License

[MIT](LICENSE)
