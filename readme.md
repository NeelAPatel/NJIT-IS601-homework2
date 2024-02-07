# Submission Details

Neel Patel\
nap48

# Installation Instructions
The goal of this project is to run `pytest --pylint --cov` and get 100% test coverage. 

1. Install Python/Pip/Virtualenv, or ensure it is installed. 
```bash
sudo apt update -y
sudo apt install python3-pip
python3 --version
pip3 --version 
pip3 install virtualenv
virtualenv --version
```
2. Clone this repo
```bash
git clone git@github.com:NeelAPatel/NJIT-IS601-homework2.git
```

3. Start Virtual environment\
Use `ls` to ensure `venv` folder is created\
Install project requirements
```bash
virtualenv venv
ls
pip3 install -r requirements.txt
```

4. Run the pytest to see 100% coverage
```bash
pytest --pylint --cov
```



