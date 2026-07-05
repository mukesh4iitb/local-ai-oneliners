# local-ai-oneliners



## Ollama:

### sources:

* <https://oneuptime.com/blog/post/2026-02-02-ollama-model-management/view>


version:

      ollama --version

list all models: 

      ollama list

Download model:

      ollama  pull model_name

Detailed information of models:

      ollama show model_name

### Specific details of model:

Show only the license information:
      
      ollama show model_name --license

Parameters:

      ollaman show model_name --parameters

Template:

      ollama show llama3.2 --template     
      
Show the modelfile (template and parameters):

      ollama show llama3.2 --modelfile
      
Show the system prompt (if defined in model):

      ollama show llama3.2 --system
      
Removing model:
      
      ollama rm model_name

Coping/rename model:

      ollama cp model_name1 model_name2
      
Size of all the ollama models:
      
      du -sh ~/.ollama
