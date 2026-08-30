# Setup

## Instructions

1. Install python package manager- `uv`
    - `Linux`: Open terminal

        ```bash
        curl -LsSf https://astral.sh/uv/install.sh | sh
        ```

    - `Windows`: Open power shell

        ```bash
        powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
        ```

    - Check the uv installation and version

        ```
        uv --version
        ```

2. installing or updating python to the latest version.

    - Syntax
    
        ```bash
        uv python install <version>
        ```

    - Example: Install latest [30/08/2026]
    
        ```bash
        uv python install 3.14.7
        ```

    - To upgrade `python` version.
    
        ```bash
        uv python upgrade
        ```

    - To List all python versions- available and installed.
    
        ```bash
        uv python list
        ```

    - To List all installed `python` versions.
    
        ```bash
        uv python list --only-installed
        ```
    

3. Create virtual environment with latest python. If python is not available, it will be installed.
    - Syntax

        ```bash
        uv venv --python <version>
        ```

    - Example

        ```bash
        uv venv --python 3.14.7
        ```

4. Create new project or initialize the existing project
    - Create new project

        ```bash
        uv init <project name>
        ```

    - Initilize existing project

        ```bash
        cd <project dir>
        uv init
        ```

5. Install dependencies 
    - Install dependencies

        ```bash
        uv add <package name>
        ```

    - Install dev dependency

        ```bash
        uv add --dev pytest
        ```

    - from `requirements.txt`

        ```bash
        uv add -r requirements.txt
        ```

    - with `pip`
        ```bash
        uv pip install -r requirements.txt
        ```

## References

1. [astral/docs](https://docs.astral.sh/uv/concepts/python-versions/#registration-in-the-windows-registry)
2. [realpython/python-uv](https://realpython.com/python-uv/)