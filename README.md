# PRE-Requisites
- Ollama installed and can be accessed by http://localhost:11434
- python v3.12.1
## Start with creating virtual environment for python runtime or use Pycharm and create a new project
```
python -m venv ./.env
```

## Clone the Github reposistory
```
git clone https://github.com/ly-yon/lawBot.git
``` 

Once created open a terminal window and Install all packages required by running:-\
```
pip install -r ./requirements.txt
```

### Ollama configuration
Before Running the program we should configure Ollama\
Not Installed? Install from [ollama](https://ollama.com/download)\
for Linux\WSL :-\
Installation:  
```
curl -fsSL https://ollama.com/install.sh | sh
```

### Pull the ollama model
Install Required Model: 
```
ollama pull azar30/law
```

### Check ollama installation and model availability
Run the command: 
```
ollama list
```
You should see a list of the available models

### Start ollama server
In a different terminal window, run the command: 
```
ollama run azar30/law
``` 

### Validate ollama server
In a browser window visit http://localhost:11434 you should see that ollama is successfully running on the correct port

## Finally run the python program in a new terminal window
```python .\index.py```
