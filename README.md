# Data Basics - Learning Project

This project contains Jupyter Notebooks designed for learning fundamental data science concepts and Python programming techniques.

## Project Structure

*   `notebooks/`: Contains the Jupyter Notebooks with tutorials and exercises.
*   `data/`:  (Potentially, but excluded from version control). May contain data files used in the notebooks. *Note: Raw and processed data subdirectories, and common data file types are ignored by version control as per `.gitignore`.*
*   `environment.yml`:  Specifies the project's Conda environment.

## Getting Started

1.  **Prerequisites:**

    *   [Anaconda](https://www.anaconda.com/download) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) is recommended for managing the environment.
    *   Poetry is used for managing dependencies.

2.  **Environment Setup:**

    *   Create the Conda environment using the `environment.yml` file:

        ```bash
        conda env create -f environment.yml
        conda activate dsc
        ```

    *   Install project dependencies using Poetry:

        ```bash
        poetry install
        ```

3.  **Jupyter Notebook:**

    *   Navigate to the `notebooks/` directory in your browser and open the desired notebook.

## Project Details

*   **Python Version:** This project is configured to use Python 3.11, as specified in `environment.yml`.
*   **Ignored Files:**  The `.gitignore` file prevents various files from being tracked by Git, including:
    *   Python bytecode (`*.pyc`, `*.pyo`)
    *   Virtual environment directories (`venv/`, `.env/`)
    *   Data files (`*.csv`, `*.dat`, `*.db`, etc. - see `.gitignore` for a complete list)
    *   Jupyter Notebook checkpoints (`.ipynb_checkpoints/`)
    *   IDE configuration files (`.idea/`, `.vscode/`)
    *   OS-specific files (`.DS_Store`, `Thumbs.db`)
    *   Large data directories (`data/raw/`, `data/processed/`)
    *   And more.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes.
4.  Submit a pull request.

## License

[Choose a license and add it here.  For example, MIT License.]