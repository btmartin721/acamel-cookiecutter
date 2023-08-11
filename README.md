# Cookiecutter PyProject Template

This is a cookiecutter template designed to set up a standardized Python project structure. It includes various subdirectories, each with its specific purpose and an accompanying README file.

Essentially, this helps us standardize the way we are doing analyses.

## Project Structure

The template creates the following directories and files:

- `align/`: Contains any alignment files used in the analysis.
- `notebooks/`: Contains Jupyter notebooks used for analysis and visualization.
- `dataprep/`: Includes files and tools for preparing and cleaning data.
- `scripts/`: Contains standalone scripts for various purposes within the project.
- `analysis/`: Includes analysis results.
- `input_files/`: Includes symbolic links to input files used in the analysis.
- `src/`: Includes source code for GitHub repositories used in the analysis.
- `bin/`: Includes compiled binaries used in the analysis.
- `run_job.sbatch`: A template slurm job submission script.

## Usage

To use this template, you'll need to have [Cookiecutter](https://github.com/cookiecutter/cookiecutter) installed. Then you can create a new project with:

```bash
cookiecutter https://github.com/btmartin721/acamel-cookiecutter

