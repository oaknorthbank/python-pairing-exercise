Pairing Exercise: Python
========================

This is a pairing exercise for prospective full-stack/back-end developers with a focus on Python.

The candidate should guide the exercise and do as much as is feasible within the time limit (~30-35 minutes).

## Workflow

The candidate can choose to use any tools, IDEs and editors they like and is expected to have some setup to be able to share their screen and write Python code.

The pairing exercise should be run following [Test-Driven Development (TDD)](https://en.wikipedia.org/wiki/Test-driven_development). The candidate doesn't need to have previous TDD experience, but some understanding of what it is at high level can be helpful.

The main idea is to start by writing a failing test with the expected behaviour of the code, and then work on it until the test passes.

## Goal

Process a list of invoices and produce the following statistics:

1. Total number of invoices per organisation
2. Total number of unpaid invoices per organisation
3. Total number of overdue invoices per organisation
4. Total number of paid invoices per organisation per month

## Setup

The exercise should not require the use of any external dependencies except for `pytest` to run the tests.

If using `pipenv`:

```bash
pipenv install --dev
pipenv run pytest .
```

Alternatively, if `pipenv` is not installed:

```bash 
pip install pytest
pytest .
```
