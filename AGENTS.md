# AGENTS.md

## Cursor Cloud specific instructions

This is the `mila-hackathon-2026` repository — a Python-based hackathon project.

### Current state

As of initial setup, this is a **blank repository** with only `README.md` and a Python `.gitignore`. No application code, dependencies, or services exist yet.

### Environment

- **Python 3.12** is available system-wide (`python3`, `pip3`).
- The `.gitignore` is configured for Python projects (covers venv, __pycache__, pytest, mypy, ruff, Django, Flask, Jupyter, etc.).
- No virtual environment or dependency files exist yet. When dependencies are added (e.g. `requirements.txt`, `pyproject.toml`), the update script should be revised accordingly.

### Development notes

- When the project gains code, add a `pyproject.toml` or `requirements.txt` and update the VM update script to install dependencies.
- Prefer `uv` or `pip` for dependency management based on what the project adopts.
