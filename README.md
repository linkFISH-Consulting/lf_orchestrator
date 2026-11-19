# linkFISH Orchestrator

Lightweight orchestration for Python workflows, built on [Hamilton](https://github.com/apache/hamilton).

## Documentation

- Published here [docs.linfish.eu](https://docs.linkfish.eu/category/linkfish-orchestrator/)

## Installation

The package is currently installed from GitHub rather than PyPI:

```bash
uv add "lf-orchestrator @ git+https://github.com/linkFISH-Consulting/lf-orchestrator.git"
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
