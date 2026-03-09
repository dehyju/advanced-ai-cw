# How to train a neural network to flag spam emails

All information found in [main.ipynb](./main.ipynb)

## Set up

### Required dependencies

You can find all required dependencies in the [requriements.txt](./requirements.txt)

### Virtual enviroment

This is because you want to isolate dependencies into its own enviroment so you don't install unneccessary dependencies outside of the virtual env.

For MacOSX

```bash
python3 -m venv venv
source venv/bin/activate
pip3 install -r ./requirements.txt
```

For Windows PowerShell

```powershell
python -m venv venv
venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

For Windows cmd

```cmd
python -m venv venv
venv\Scripts\activate.bat
pip install -r requirements.txt
```