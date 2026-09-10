We welcome contributions to STELLAR-PATH tools and repositories!

## Ground Rules
- Be respectful and follow our [Code of Conduct](CODE_OF_CONDUCT.md).
- Ensure all CI tests and linters pass before opening a pull request.
- Keep pull requests focused on a single change or feature.

## Development Workflow
1. Fork the repository and create your branch from `main`.
2. Ensure unit tests and lint checks run cleanly:
   - Rust: `cargo check`, `cargo test`, `cargo clippy`
   - Go: `go vet ./...`, `go test ./...`
   - Node/TS: `npm run lint`, `npm test`, `npm run build`
3. Commit with conventional commit messages (e.g., `feat:`, `fix:`, `docs:`).
4. Submit a Pull Request targeting `main`.
