## NVM

1. Execute: `winget install CoreyButler.NVMforWindows`

## Python

1. Remove all python versions and remove extra path variables (windows apps)
2. Download latest python from [Python.org](https://www.python.org/downloads/)
3. Install [pyenv-win](https://github.com/pyenv-win/pyenv-win)
   - > `Invoke-WebRequest -UseBasicParsing -Uri "https://raw.githubusercontent.com/pyenv-win/pyenv-win/master/pyenv-win/install-pyenv-win.ps1" -OutFile "./install-pyenv-win.ps1"; &"./install-pyenv-win.ps1"`
4. Install pipx (`python -m pip install --user pipx`)
   - Navigate to AppData/Roaming/Python/Python3xx/Scripts and execute (`pipx ensurepath`)
5. Install Poetry (`pipx install poetry`)
