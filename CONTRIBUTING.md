# Contributing to GeoLang

Thank you for your interest in contributing!

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone git@github.com:YOUR_USERNAME/REPOSITORY.git`
3. Create a branch: `git checkout -b feature/my-feature`
4. Make your changes
5. Run the lint and test commands from the repository's `.github/workflows` files, with the same feature flags. A job with only a `uses:` line runs the commands in the workflow it names, for example [rust-ci.yml](https://github.com/GeoLang/.github/blob/main/.github/workflows/rust-ci.yml)
6. Commit and push
7. Open a Pull Request

## Code Standards

- **Formatting**: Run the repository's formatter before committing
- **Linting**: The repository's lint command must pass cleanly
- **Testing**: All new functionality must include tests
- **Comments**: No doc comments. Comment only a fact the code cannot show, such as library behaviour or the measurement behind a constant
- **Dependencies**: In repositories with a `deny.toml`, run `cargo deny check` to verify license compliance

## Pull Request Process

1. If the repository has a CHANGELOG.md, add your changes in the format of its newest entries
2. Ensure CI passes
3. Request review from a maintainer
4. Squash commits before merge if requested

## Reporting Issues

- Use GitHub Issues for bug reports and feature requests
- Include steps to reproduce for bugs
- In Rust repositories, include your Rust version (`rustc --version`)

## License

By contributing, you agree that your contributions will be licensed under AGPL-3.0-or-later.
