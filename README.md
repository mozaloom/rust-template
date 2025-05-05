# Rust Project Template

A robust starting point for new Rust projects with integrated development tooling and workflows.

## Features

- Pre-configured Makefile with common development commands
- Standard project structure following Rust best practices
- Integrated linting, formatting, and testing workflows

## Getting Started

1. Create a new Rust project:
   ```bash
   cargo new <project_name>
   ```

2. Navigate to the project directory:
   ```bash
   cd <project_name>
   ```

3. Add the Makefile to your project:
   ```bash
   mv /path/to/Makefile .
   ```

4. Start building your application!

## Development Commands

| Command | Description |
|---------|-------------|
| `make rust-version` | Display all Rust toolchain versions |
| `make format` | Format code using rustfmt |
| `make lint` | Run clippy for static code analysis |
| `make test` | Run the test suite |
| `make run` | Build and run the project |
| `make release` | Build an optimized release binary |
| `make all` | Run format, lint, test, and run in sequence |

## Project Structure

```
.
├── Cargo.toml       # Project configuration and dependencies
├── Makefile         # Development automation
├── src/
│   └── main.rs      # Application entry point
└── tests/           # Integration tests
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## References

* Based on [rust-cli-template](https://github.com/kbknapp/rust-cli-template)
* [The Rust Programming Language Book](https://doc.rust-lang.org/book/)
* [Rust By Example](https://doc.rust-lang.org/rust-by-example/)