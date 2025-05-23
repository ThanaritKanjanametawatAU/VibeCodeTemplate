# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Structure

This is a template codebase with the following directories:
- `docs/` - Documentation files
- `specs/` - Specification documents

## Development Setup

Since this is a template project, specific commands will depend on the technology stack chosen. Common patterns:

### For Node.js projects:
- `npm install` or `yarn install` - Install dependencies
- `npm run dev` or `yarn dev` - Start development server
- `npm test` or `yarn test` - Run tests
- `npm run build` or `yarn build` - Build for production
- `npm run lint` or `yarn lint` - Run linting

### For Python projects:
- `pip install -r requirements.txt` - Install dependencies
- `python -m pytest` - Run tests
- `python -m black .` - Format code
- `python -m flake8` - Run linting

### For Rust projects:
- `cargo build` - Build project
- `cargo test` - Run tests
- `cargo run` - Run project
- `cargo fmt` - Format code
- `cargo clippy` - Run linting

## Claude Code Automation Commands

This repository includes automation commands in the `.claude/commands/` directory. These commands can be invoked using the following syntax:

```
project:<command_name> [arguments]
```


## Notes

This is a template repository. Update this file with specific commands and architecture details once the actual codebase is implemented.