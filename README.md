# Personal Assistant

## Installation

Install the package
```shell
pip install .
```

```shell
pip install ".[dev]"
```

Install pre-commit hook
```shell
pip install pre-commit && pre-commit install
```

## Format & Lint
Fix format
```shell
ruff check . --fix
```

Quality control
```shell
mypy assistant tests
```

## Testing
Install development dependencies

Run tests
```shell
PYTHONPATH=. pytest 
```

