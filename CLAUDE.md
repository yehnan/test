# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

Python 3.13 project managed with [uv](https://docs.astral.sh/uv/).

## Commands

```bash
# Run the program
uv run main.py

# Add a dependency
uv add <package>

# Sync dependencies (after pulling changes)
uv sync
```

## Structure

Entry point is `main.py`. The `main()` function is called when run directly.
