# linkFISH Orchestrator

Lightweight orchestration for Python workflows, built on [Hamilton](https://github.com/apache/hamilton).

The goal is to provide simple, composable tooling for running Python workflow steps, while the main stack stays focused on collecting and pinning dependencies.

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
