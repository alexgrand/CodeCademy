
# CodeCademy Learning Materials




## Prerequisites

- `pyenv` installed
- `poetry` installed


## How to use and add courses/materials

1. To add new materials or course use command:
```bash
poetry new --name=<project_name> <folder_name_to_create>
```
2. Navigate to the required folder `cd <folder_name>` 
3. Install required python version and make it local to your project with pyenv:
```bash
pyenv install 3.10
pyenv local 3.10
```
4. Verify required python version is installed:
```bash
python -V
```
5. Install poetry env and activate it:
```bash
poetry env use python
poetry shell
```
6. Update `pyproject.toml` file with required info and python version
7. Add requirements for your project:
```bash
poetry add <requirement_1> <requirement_2> -v
```
8. Install requirements in your env:
```bash
poetry install
```
9. Run needed actions. Example:
```bash
jupyter lab
```
