# Python programming playground

## Setup

1. Install development / system dependencies _(read below)_
2. Set configuration _(read below)_
3. Create and activate Python virtual environment:
   - `poetry install`
   - `poetry shell`
4. Run: `python src/main.py`

## Development / System dependencies

| System dependency                   | Required version | Description              |
| :---------------------------------- | :--------------- | :----------------------- |
| [Poetry](https://python-poetry.org) | `1.8.x`          | `Python` package manager |
| [Python](https://python.org)        | `3.12.2`         | `Python` runtime         |

## Configuration

### Poetry

#### Create a virtual environment in the project folder

Set [`virtualenvs.in-project`](https://python-poetry.org/docs/configuration#virtualenvsin-project)
configuration parameter:

- By running command: `poetry config virtualenvs.in-project true`
- By editing [configuration](https://python-poetry.org/docs/configuration/#config-directory)
  manually:
  ```toml
  [virtualenvs]
  in-project = true
  ```

#### Update dependencies and bump their versions

- Install [`up`](https://github.com/MousaZeidBaker/poetry-plugin-up) plugin:
  `poetry self add poetry-plugin-up`
- Update dependencies to latest available compatible versions: `poetry up --latest`
