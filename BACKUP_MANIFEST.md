# Excluded local artifacts

The local source tree contains generated or environment-specific content ignored by Git:

- `.venv/`: Python virtual environment.
- `.pytest_cache/`, `.ruff_cache/`, `src/**/__pycache__/`, and `tests/**/__pycache__/`: tool caches and bytecode.
- `.xh-index/` and `runs/`: local index and generated run outputs.

These remain on the cluster and should be copied separately if needed.
