# Python Starter Template

Use this template for normal Python analysis projects.

```bash
uv sync
```

VS Code/Cursor:

- Run normal scripts with the selected `.venv` interpreter.
- Use **Run Task... → uv run current file** to run the current file through
  `uv run`.
- Use **Run and Debug → Python: Current file** to debug after an automatic
  `uv sync`.
- Use **Python: Current file (locked env)** once `uv.lock` is committed and you
  want the IDE to fail if the lockfile is stale.

For standalone JupyterLab, run:

```bash
lab-setup
```
