# Deep Learning Lab 01

This repository contains the notebooks for Lab 01:

- [task1_numpy_matplotlib_seaborn.ipynb](task1_numpy_matplotlib_seaborn.ipynb)
- [task2_au_nanoparticle.ipynb](task2_au_nanoparticle.ipynb)

## Requirements

- Python 3.10 or newer
- Visual Studio Code
- Jupyter extension for VS Code

## Setup on Windows (PowerShell)

From the project root, run:

```powershell
cd "D:\SLIIT\Deep Learning - SE4050\Lab\Lab 01\SE4050-DL-Lab1"
py -3 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python -m pip install jupyter ipykernel
python -m ipykernel install --user --name venv --display-name "Python (venv)"
```

If PowerShell blocks the activation script, run this once for the current terminal session:

```powershell
Set-ExecutionPolicy -Scope Process RemoteSigned
```

## Run the notebooks

Option 1: In VS Code

1. Open a notebook file.
2. Select the kernel named "Python (venv)" or the .venv interpreter.
3. Run the cells in order.

Option 2: From the terminal

```powershell
jupyter lab
```

Then open the notebook you want to run in the browser.

## Troubleshooting

If you see an import error such as "No module named seaborn", make sure:

- the notebook is using the same Python environment as the virtual environment you created,
- the notebook kernel was restarted after installation,
- the selected interpreter is .venv\Scripts\python.exe.
