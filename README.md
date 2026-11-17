# linkFISH Orchestrator

Lightweight orchestration for Python workflows, built on [Hamilton](https://github.com/apache/hamilton).

This project was split out of the Python/DBT stack so it can be developed and released independently.
The main stack stays focused on collecting and pinning dependencies, while this package owns the orchestration tooling.

## Documentation

- [Orchestration guide](docs/orchestration.md)
- [Environment variables](docs/env_vars.md)

## Installation

```bash
uv sync
```

## Development

```bash
# install all development dependencies
uv sync --group dev

# lint and format
uv run ruff check .
uv run ruff format .

# type checking
uv run mypy .

# tests
uv run pytest
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for the full text.

This project builds on and incorporates third-party open-source tools and libraries. Those components retain their original copyright and license notices, and their original licenses — which may differ from the MIT License — continue to govern their use.
