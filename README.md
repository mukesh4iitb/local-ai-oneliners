# Local-ai-oneliners



## Ollama:

### Sources:

* <https://oneuptime.com/blog/post/2026-02-02-ollama-model-management/view>


Version:

      ollama --version

List all models: 

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

      ollama show model_name --template     
      
Show the modelfile (template and parameters):

      ollama show model_name --modelfile
      
Show the system prompt (if defined in model):

      ollama show model_name --system
      
Removing model:
      
      ollama rm model_name

Coping/rename model:

      ollama cp model_name1 model_name2
      
Size of all the ollama models:
      
      du -sh ~/.ollama
