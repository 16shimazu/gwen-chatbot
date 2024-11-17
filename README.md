# gwen-chatbot V2  
 A somewhat simple discord.py chatbot that uses any selfhosted model through ollama.   
 gwen-chatbot is **probably not** ready full-scale deployment.  
  
The AIs prompt is preconfigured in the code, so system parameters are optional.  
   
 **Requirements:**  
 > 1. Python (Latest Version should work. It has been tested and works with Python 3.11)
 > 2. Module dependencies: `python -m pip install discord requests aiohttp asyncio json`.
 > 3. Install [Ollama](https://ollama.com/).  
 > 4. Download a [Model](https://ollama.com/search).  
 > 5. [download](https://github.com/16shimazu/gwen-chatbot/archive/refs/heads/main.zip) gwen.py and config.json.  
  
 **setup:**  
 1. Edit the config.json (**READ THE COMMENTS IN THE CODE BEFORE RUNNING.**) 
 
 GUI:
 > 2. In a command prompt window, run `ollama run <model name>`
 > 3. In a second command prompt window, run `python <path/to/gwen.py>`
 
 CLI only:
 > 2. in `tmux` run `ollama run <model>`
 > 3. in a seperate `tmux` session run `python <path/to/gwen.py>`
 
discord: `sulfur.shimazu`