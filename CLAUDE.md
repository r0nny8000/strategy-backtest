# Agent Instructions

This file provides guidance to Agents like Claude Code or Codex when working on this project.

## Project Overview

Refer to [README.md](README.md) for project objectives, requirements, and documentation.

## generating Markdown Files

- please avoid bold and italics in generated Markdown files

## Development Guidelines

- Follow existing code style and conventions
- Keep code simple and readable
- Write tests for new functionality

## Git Workflow

### Before Commiting

- Run `uv run python -m pytest` and ensure all tests pass before committing
- Review staged changes with `git diff --staged` before committing
- Review README.md and update if necessary to reflect any new features or changes

### Commiting

- Write clean, readable commit messages:
  - Use imperative mood (e.g. "Add feature" not "Added feature")
  - Keep the subject line concise (50 chars or less)
  - Add a body if more context is needed, separated by a blank line

### Pushing

- Do not push to remote until all tests pass locally
