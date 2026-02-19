# Agent Instructions

This file provides guidance to Agents like Claude Code or Codex when working on this project.

## Project Overview

Refer to [README.md](README.md) for project objectives, requirements, and documentation.

## generating Markdown Files

- please avoid bold and italics in generated Markdown files, as they can cause rendering issues in some environments

## Development Guidelines

- Follow existing code style and conventions
- Keep code simple and readable
- Write tests for new functionality

## Git Workflow

- Run `uv run python -m pytest` and ensure all tests pass before committing
- Write clean, readable commit messages:
  - Use imperative mood (e.g. "Add feature" not "Added feature")
  - Keep the subject line concise (50 chars or less)
  - Add a body if more context is needed, separated by a blank line
- Review staged changes with `git diff --staged` before committing
- Do not push to remote until all tests pass locally
