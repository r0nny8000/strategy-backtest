# CLAUDE.md

This file provides guidance to Claude Code when working on this project.

## Project Overview

Refer to [README.md](README.md) for project objectives, requirements, and documentation.

## Tech Stack

- Python (see `pyproject.toml` for version and dependencies)

## Development Guidelines

- Follow existing code style and conventions
- Keep code simple and readable
- Write tests for new functionality
- Run tests before committing: `python -m pytest`

## Git Workflow

- Run `python -m pytest` and ensure all tests pass before committing
- Write clean, readable commit messages:
  - Use imperative mood (e.g. "Add feature" not "Added feature")
  - Keep the subject line concise (50 chars or less)
  - Add a body if more context is needed, separated by a blank line
- Review staged changes with `git diff --staged` before committing
- Do not push to remote until all tests pass locally
