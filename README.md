# python_devops
[Source https://www.youtube.com/watch?v=kwZNpieUreA]

  ### I want to learn cloud development best practices and deepen Python language.

1. Create virtaul environment: `virtualenv ~/.venv`
2. Edit `~/.bashrc`: adding as last line `source ~/.venv/bin/activate`, when opening the terminal, the virtual environment starts.
3. Libraries and their installation process
  - `requirements.txt` contains all the needed libraries
  - In `Makefile` there is the process for installing them
  - `make install` starts the proccess of intalling all the libraries
  - `pip freeze` and in requirements.txt write the version for compatibility
  