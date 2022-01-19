# Bindra Lab Bioinformatics Setup
For Windows computers.  

## Install Required Software

- WSL/Ubuntu-20.04
  - Default password is `changeme!`. Use the command `passwd` to set a new one.
  - `sudo apt-get update && sudo apt-get upgrade`
- VSCode
  - Install extensions: Python, Jupyter, Remote Development, R
- git
- pyenv-win
  - Ensure execution aliases are turned off for python: Windows Menu search "alias"
  - `pyenv install 3.9.6`

Ideally can do so via `choco` but will need IT help for the Yale computers.

## Get Bindra Lab Source Code
If you do not have a GitHub.com account, make one and ask Sam to add you to the Bindra org.

### Example: downloading NAPRT-analysis repository
- `git clone https://github.com/bindralab/NAPRT-analysis.git` # Download the latest version of the repository
- `code NAPRT-analysis` # Open a VSCode window for the repository
