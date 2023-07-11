# Python programming playground

## Setup

1. Install development / system dependencies _(read below)_
2. Set configuration _(read below)_
3. Create and activate Python virtual environment:
   - `poetry install`
   - `poetry shell`
4. Run: `python src/main.py`

## Development / System dependencies

| System dependency                   | Minimum version | Description              |
| :---------------------------------- | :-------------- | :----------------------- |
| [Poetry](https://python-poetry.org) | `1.4+`          | `Python` package manager |
| [Python](https://python.org)        | `3.11+`         | `Python` runtime         |

## Configuration

### Poetry

- Set the following
  [`Poetry` configuration](https://python-poetry.org/docs/configuration/#config-directory) parameter
  in order to create a virtual environment in the project folder:
  ```toml
  [virtualenvs]
  in-project = true
  ```
