# test-clearml-agent

Project to test ClearML remote agent

## Requires

- poetry >= 1.2.0

    ```bash
    curl -sSL https://install.python-poetry.org | python3 -
    ```

    or go [official](https://python-poetry.org/docs/#installing-with-the-official-installer)

## Prepare

- Install dependencies `poetry install -n`

## Execution requirement

- Poetry files have to be on the root level
- Agent have to be started without `docker` mode or `poetry install` fails with return error 1
