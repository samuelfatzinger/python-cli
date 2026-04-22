# python-cli

A sample Python command-line interface built with `click`.

## Overview

This project demonstrates a simple CLI structure using the `click` library. It includes two example commands that accept arguments and print output to the console.

## Requirements

- Python 3
- click

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/mengwangk/python-cli.git
cd python-cli
pip install click
```

## Usage

Run commands from the project root:

```bash
python cli.py [COMMAND] [ARGS]
```

## Commands

### command1

```bash
python cli.py command1 SRC_DB DEST_DB
```

Prints the provided arguments.

### command2

```bash
python cli.py command2 SRC_DB DEST_DB
```

Prints the provided arguments and outputs a value from the configuration.

## Project Structure

```text
cli.py
cli/
tests/
Pipfile
README.md
```

## Notes

This project appears to be a minimal or example CLI and may not represent a complete application.
