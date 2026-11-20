
# University Calculator Lab Project

A simple Python calculator developed for the SCCM4910 DevOps module.

## Requirements

- Python 3
- pytest (for automated testing)

## Running the calculator

Run the startup script:

```bash
./run.sh
```

Enter two numbers and an operator (+, -, *, /).

Example:
- First number: 6
- Operator: *
- Second number: 7
- Result: 42.0

Press Ctrl+C to stop the calculator.

## Running automated tests

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install the testing dependencies:

```bash
python3 -m pip install -r requirements-dev.txt
```

Run the quality gate:

```bash
./check.sh
```

Expected result:
- 5 tests passed
- QUALITY GATE PASSED
- Exit status 0

A non-zero exit status indicates a test failure or another error. The quality gate can be used to check changes before merging.
