 Awesome Project name my1 repos

A minimal Python template for quickly starting projects on GitHub.  
This repo includes a standard project structure, unit tests with `pytest`, CI with GitHub Actions, and pre-commit hooks.

## Features 
- Standard `src/` and `tests/` layout
- Unit testing with `pytest`
- GitHub Actions for CI (lint + tests)
- MIT License
- Pre-commit hooks (Black + Ruff + Prettier)

## Quickstart first start
```bash
# 1) Unzip and move into project
unzip awesome_project.zip -d awesome_project
cd awesome_project new

# 2) Create virtual env and install deps
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -U pip
pip install -r requirements.txt
pip install -r requirements-dev.txt

# 3) Run the project
python -m awesome_project --name "World"

# 4) Run tests
pytest

# 5) Enable pre-commit (optional)
pre-commit install

# 6) Push to GitHub
git init
git add .
git commit -m "Initial commit: Python template"
git branch -M main
git remote add origin YOUR-REPO-URL
git push -u origin main
# myrepos
