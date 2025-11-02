Python Tests Project

This is a simple, self-contained Python test project with 100 tests, intended for demonstrating and validating test runners.

Structure:
- tests/: contains 10 test files, 10 tests each (total 100 tests)
- requirements.txt: minimal dependencies
- pytest.ini: pytest configuration

Quick start
1) Create a virtual environment (recommended)
   - macOS/Linux:
     python3 -m venv .venv && source .venv/bin/activate
   - Windows (PowerShell):
     python -m venv .venv; .venv\\Scripts\\Activate.ps1

2) Install dependencies
   pip install -r requirements.txt

3) Run the tests
   pytest
   # or with verbose output
   pytest -q

Notes
- All tests are simple and deterministic. They cover basic Python features (math, strings, lists, dicts, sets) and small helper functions defined inline in the tests.
- No network or file system access is required.
