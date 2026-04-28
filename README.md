# test

A simple Python 3.13 project managed with [uv](https://docs.astral.sh/uv/).

## Requirements

- Python 3.13+
- [uv](https://docs.astral.sh/uv/)

## Installation

```bash
# Clone the repository
git clone https://github.com/yehnan/test.git
cd test

# Sync dependencies
uv sync
```

## Usage

```bash
uv run main.py
```

Output:

```
Hello World
```

## Development

```bash
# Add a dependency
uv add <package>

# Sync dependencies (after pulling changes)
uv sync
```

## Project Structure

```
test/
├── main.py        # Entry point
├── pyproject.toml # Project metadata and dependencies
└── README.md
```
