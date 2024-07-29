# PRE-Requisutes
- Ollama installed and can be accessed by http://localhost:11434
- python v3.12.1
## Start with creating virtual environment for python runtime
```python -m venv ./.env ```\
Once created Install all packages required by running:-\
```pip install -r ./requirements.txt```\
Before Running the program we should configure Ollama\
Not Installed? Install from [ollama](https://ollama.com/download)\
for Linux\WSL :-\
Installation:  ```curl -fsSL https://ollama.com/install.sh | sh```\
Install Required Model: ```ollama pull azar30/law```
## Finally run the python program
```python .\index.py```
