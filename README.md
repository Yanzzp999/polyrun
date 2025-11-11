# polyrun

A small Go utility for running and managing processes (lightweight runner).

## Features

- Minimal CLI for executing commands and simple process orchestration
- Designed to be used as a library or standalone tool

## Installation

Install the latest released version:

```bash
go install github.com/Yanzzp999/polyrun@latest
```

Or add as a dependency in your module:

```bash
go get github.com/Yanzzp999/polyrun@latest
```

## Usage

If the repository provides a `main` executable, after `go install` the binary will be available in `$GOBIN` or `$GOPATH/bin`.

Example (run from another module):

```go
import "github.com/Yanzzp999/polyrun"

// use polyrun package API here
```

For CLI usage, refer to the code examples in the repository.

## Contributing

Contributions are welcome. Please open issues or pull requests on GitHub.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact

Author: Yanzzp999 (see GitHub profile)
