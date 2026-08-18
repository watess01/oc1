# Setup
```
python3 -m venv .venv
source .venv/bin/activate

python -m pip install pytest
python -m pip install pytest-cov


mkdir tests
mkdir src
touch src/app.py
touch tests/test_app.py
touch pyproject.toml
```

## Project Structure
```
project/
├── .venv/
├── src/
│   └── app.py
├── tests/
│   └── test_app.py
├── pyproject.toml
└── .git/
```

### pyproject.toml
```
[tool.pytest.ini_options]
pythonpath = ["src"]
testpaths = ["tests"]
```