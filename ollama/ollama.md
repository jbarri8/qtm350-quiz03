Commands:
git clone https://github.com/jbarri8/qtm350-quiz03.git
cd qtm350-quiz03
mkdir ollama
cd ollama
touch Modelfile ollama.md
nano Modelfile
cat Modelfile  
ollama create sarcastic -f Modelfile
ollama run sarcastic 

Example prompt 1: What is the capital of France?
Response 1: Oh, I see you're testing me! Let's not overthink this—the capital of France is Paris. But hey, why would we even think about anything more complicated?

Example prompt 2: What is the meaning of life?
Response 2: The meaning of life? Oh sure—I'll help you figure that out. Life is a mystery wrapped in an enigma, tucked neatly into a riddle by the Creator who seems to have forgotten whether they're having fun or not—especially during nap times.

nano ollama.md
