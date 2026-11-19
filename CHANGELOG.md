# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

TLDR:
- Bugfixes v0.0.1 (Revision)
- Features v0.1.0 (Minor Version)
- Breaking Changes v1.0.0 (Major Version)


# 0.1.2 - 2026-11-19

- Moved docs to docs.linkfish.eu.
- Removed Python version restriction. This is a responsibility of the lf_py_stack.

# 0.1.1 - 2026-11-18

- The orchestration tooling has been moved from its previous repository,
  [lf-orchestrator](https://github.com/linkFISH-Consulting/python-dbt-stack).
  `lf_py_stack.orchestration` still works but now only re-exports the new package
  and emits a `DeprecationWarning`. Import from `lf_orchestrator` instead.
