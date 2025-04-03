# MLE course 2025-04

Here we learn how to do Machine Learning Engineering stuff. Based of the course in this repository: https://github.com/alexeygrigorev/ml-engineering-contsructor-workshop

## how to install UV

Jus run "curl -LsSf https://astral.sh/uv/install.sh | sh"

## Day 1

-Create a folder named "day_1"
-in the console (terminal) run "cd day_1" to change the current directory to day_1
-run "uv init --python 3.10"
    -creates files in the day_1 folder and installs python 3.10
-run "uv sync"
    -create a virtual python environment
    -can install packages in this virtual environment specific to the project

## install dependencies
-run "uv add scikit-learn==1.2.2 pandas pyarrow"
## dependencies only needed in development
-run "uv add --dev jupyter seaborn"
-run "uv run jupyter notebook" allows you to open juputer notebook in browser and ensure you have the right kernel