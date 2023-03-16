[![Test Multiple Python Versions](https://github.com/flazzari/python_devops/actions/workflows/main.yml/badge.svg)](https://github.com/flazzari/python_devops/actions/workflows/main.yml)

# python_devops
[Source https://www.youtube.com/watch?v=kwZNpieUreA]

  ### I want to learn cloud development best practices and deepen Python language.

### Cloud structure project
1. Create virtaul environment: `virtualenv ~/.venv`
2. Edit `~/.bashrc`: adding as last line `source ~/.venv/bin/activate`, when opening the terminal, the virtual environment starts.
3. Libraries and their installation process
  - `requirements.txt` contains all the needed libraries while `Makefile` conatains the process for installing them
  - `make install` starts the proccess of intalling all the libraries
  - `pip freeze` and in requirements.txt write the version for compatibility
  - `make lint` probably static code analisys

### Github Actions

Created my own Github Action `main.yml` with instruction to test different python versions. Foreach version it runs the commands inside the makefile.

#### Status Badge
After performig Github actions, there is the option to create a 'Status Badge' that resume the situation of the project like this:
[![Test Multiple Python Versions](https://github.com/flazzari/python_devops/actions/workflows/main.yml/badge.svg)](https://github.com/flazzari/python_devops/actions/workflows/main.yml)


