# Rule Engine with AST

This repository contains a small Flask-based rule engine that uses an abstract syntax tree representation for conditional logic.

The project was built around a straightforward systems idea: instead of hardcoding eligibility logic directly into the application, represent rules as structured expressions that can be created, combined, and evaluated more flexibly.

## What this repo does

- creates and stores rules
- evaluates rules against input attributes such as age, department, income, or spend
- combines multiple rules with logical operators
- exposes a simple UI and backend flow for working with those rules

## Main files

- `app.py`
  Core Flask application and rule-engine logic.
- `templates/`
  Basic frontend templates for interacting with the app.
- `requirements.txt`
  Python dependencies.

## Running locally

Install dependencies:

```bash
pip install -r requirements.txt
```

Start the app:

```bash
python app.py
```

## Why this repo matters

This is an earlier backend-oriented project, but it is still a useful example of application logic design rather than just UI work. The AST-based rule representation is the part that makes it interesting.
