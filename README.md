# PaceLink Project Documentation

This repository hosts the documentation for the PaceLink project.

## Live Documentation

The documentation is automatically generated and published using GitHub Pages. You can view the live site here:

**[https://taixmiguel.github.io/pace-link-wiki/](https://taixmiguel.github.io/pace-link-wiki/)**

## About This Repository

This repository contains all the source files used to build the documentation website. It uses [MkDocs](https://www.mkdocs.org/) with the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.

Changes pushed to the `main` branch will automatically trigger a new deployment of the documentation site.

## Local Development

To work on the documentation locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/TaixMiguel/pace-link-wiki.git
    cd pace-link-wiki
    ```

2.  **Create a virtual environment and install dependencies:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use: venv\Scripts\activate
    pip install -r requirements.txt
    ```

3.  **Run the local development server:**
    Navigate to the directory containing the `mkdocs.yml` file and run the `serve` command:
    ```bash
    cd PaceLink-wiki
    mkdocs serve
    ```

    Open your browser and go to `http://127.0.0.1:8000` to see the local version of the documentation. Changes you make to the source files will be automatically reloaded.

    > **Note:** If port 8000 is already in use, you can specify a different port with the `--dev-addr` flag:
    > ```bash
    > mkdocs serve --dev-addr 127.0.0.1:8001
    > ```
