# New prj

python3 -m venv .venv
source .venv/bin/activate
python -m pip install pytest
mkdir tests
mkdir src

## structure
require
 - src/app.py
 project.toml
 .git


## installs 
 python -m pip install pytest

## minimum pyproject.toml
``` 
[tool.pytest.ini_options]
pythonpath = ["src"]
testpaths = ["tests"]
```
