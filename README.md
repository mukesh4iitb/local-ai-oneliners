# local-ai-oneliners

## Ollama:
   
   ollama --version

ollama list

ollama  pull model_name

ollama show model_name

# To be more specific informations:
# Show only the license information
ollama show llama3.2 --license

# Show the modelfile (template and parameters)
ollama show llama3.2 --modelfile

# Show the system prompt if defined
ollama show llama3.2 --system

# Show the prompt template
ollama show llama3.2 --template

ollama rm model_name

ollama cp model_name1 model_name2


Extract fields 2, 4, and 5 from file.txt:

    awk '{print $2,$4,$5}' input.txt


Print each line where the 5th field is equal to ‘abc123’:

    awk '$5 == "abc123"' file.txt
