# TD_WL_Ecole_Rodolphe_Cledassou
TDs de weak lensing de l'école d'été Euclid - Rodolphe Clédassou

## Installation

First, downoad this repository by typing
```bash
git clone git@github.com:martinkilbinger/TD_WL_Ecole_Rodolphe_Cledassou.git
```
(The download link is also available under the green button on the top right.)

There are several options to install the few python libraries required to run the notebooks.

### Option 1: With `pip`.

Simply type

```bash
pip install -r requirements.txt --user
```
This might however create conflicts with existing packages. A safer options is described next.

### Option 2: With `poetry`.

First, if the command `poetry` does not exist, install the package via
```bash
pip install poetry --user
```

Then type

```bash
poetry shell
poetry install
```
These commands install the libraries in an isolated virtual environment and leave any other `python` library installations untouched.

## Run

Type
```bash
jupyter-notebook
```
and choose in the file explorer the notebook to run.





