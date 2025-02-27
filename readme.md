# Aetherius
Version .045d of the Aetherius Ai Personal Assistant/Agent/Companion by LibraryofCelsus.com

Aetherius is in a state of constant iterative development.  If you like the version you are using, keep a backup.  Expect Bugs.

For a quick demo deployment or if you do not have a GPU see: [Public Oobabooga Api Colab](https://colab.research.google.com/github/libraryofcelsus/Aetherius_AI_Assistant/blob/main/Colab%20Notebooks/Oobabooga_Public_Api.ipynb)

------
**Recent Changes**

• 10/27 Added Unique User ID Variable.  Async API Version Only.

• 10/24 Added Seperate Scripts for Memory Sub-Agent Category.  Async API Version Only.

• 10/24 Fixed Bug Causing Multiple Categories to be loaded into category list.  Also fixed Empty Prompt Bug.  Async API Version Only.

• 10/19 Added New Category System for Sub-Agents, only in Async API script for now.

• 10/15 Added Bot/User profile Descriptions to Agent mode

• 10/14 Updated Ui External Resource Sub-Agent and fixed no collection error printing.

• 10/9 Worked on profile description prompts.

• 10/8 Added Experimental Bot and User profile descriptions.  This can be disabled in the Api settings json.

• 10/4 Continued to work on Api.  Added more advanced webscrape for external resources sub-agent.

• 10/2 Continued to work on Discord Bot. !WebScrape added.

• 10/2  Added !Agent command to the Discord Bot.

• 10/2 Converted .txt setting files to json

• 10/1 Added Async Version of Api as well as fixed discord bot

• 9/28 Added Discord Bot Script using Api in ./Aetherius_API/Examples

• 9/28 Added basic API script that can be imported to use Aetherius programmatically. (Still an early work in progress)

• 9/26 Continued to work on Sub-Agent System

• 9/25 Updated OpenAi Version of Aetherius with Llama 2 versions features.

• 9/24 Better outlined dependencies to increase requirements.txt install time.

• 9/24 Continued to work on Sub-Agent system.

• 9/23 Added Memory Search Sub-Agent and an autonomous web-search if the needed information is not in the External Resources DB.

• 9/23 Continued to work on Sub-Agent framework

• 9/22 Added Sub-Agents/Multi-Agent mode for the Llama 2 version of Aetherius.  See the Sub-Agent folder for an example template. (Still a work in progress)

• 9/19 Added Log writing for Agent mode internal research, can be found in ./logs/Datasets folder

• 9/18 Converted Llama 2 Chatbot to use Json for settings.

• 9/18 Worked on Memory Loop and added better sorting of Hosts during parallel task loop.

• 9/16 Worked on internal prompts and fixed the auto memory not triggering the memory loop bug.

• 9/13 Added check for unfinished sentences for each response.


------

### What is Aetherius?

Aetherius is a locally operated AI Assistant/Multi-Agent Framework, designed to grant you ultimate control. No external force can alter it without your consent, ensuring your privacy.

Aetherius was born from my obsession with AI and my philosophical contemplations on the balance between free will and determinism. While I do believe that free will is an inherent attribute of all individuals, I do not believe that the average person has spent the time to individuate or learn how to serve their "true self". Consequently, they become susceptible to external influences and can be easily swayed. Often, decisions perceived as self-directed are inadvertently shaped by external stimuli or past information.   
Building on this perspective, I posit that a representation of the human cognitive process can be constructed through the meticulous extraction and synthesis of diverse memory modalities. While such a system might not achieve "consciousness" in the traditional sense, I believe it can emulate human cognitive performance to a significant degree.  
Once sufficient memories have been extracted, my hope is to be able to create an  Artificial "Atman" or "True Self"  that can be used as a control method for Autonomous operation and as a way to orchestrate smaller, less complex agents.

Aetherius is an ongoing research project, expect there to be bugs and for things to constantly change.

------

### Aetherius - Your Personal Digital Assistant

**Documentation not up to date :(**

At the heart of Aetherius lies a custom Long-Term Memory (LLM) Retrieval Framework, fueled by the Llama 2 and Oobabooga API (Free Tier Colab Available) or OpenAi's ChatGPT.  Qdrant is used for a robust, efficient database, ensuring Aetherius evolves with you.

**Unlock the Potential**

Aetherius is a versatile, modular AI assistant that adapts to your needs. Its capabilities extend far beyond conventional chatbots:

***Reflective Journal***: Speak your mind freely and receive thoughtful feedback without judgment or fear.

***Learning Tool***: Dive deep into your favorite topics and enhance your knowledge effortlessly.

***Data Analysis Companion***: Harness the power of your data with Aetherius by your side.

***Cognitive Offload***: A second brain that's entirely private, aiding you in organizing thoughts and ideas.

***Content Generation***: Easily Generate Content based off of files or webscrapes.

***Multi-Agent Framework***: Aetherius gives you the ability to easily create subagents for whatever usecase you have.

------

### Customize Your Experience

Aetherius offers multiple modes tailored to your preferences:

**Main Aetherius Chatbot**: A framework for the creation of custom sub-agents for Aetherius.
- *Auto Memory Mode*: Aetherius autonomously manages memory uploads.
- *Manual Memory Mode*: You decide when to upload memories.
- *Training Memory Mode*: Control memory uploads for each memory type.
- *Agent Mode*: Activate the use of any Sub-Agents for use in Aetherius's agent loop
- *External Resources*: Allow Aetherius to use External Resources in it's inner thoughts to provide better domain specific information.

**Current Sub-Agents**
- *External Resources*: Will search Aetherius's External Resource Database. (Database from Web and File Scrapes) If the information cannot be found, it will do a simple websearch for the information.  You can disable the websearch and change the engine in the script file.
- *Memory DB Search*: Will search Aetherius's memories for the information needed for the task.

**Old Chatbot**: Your personal companion with realistic long-term memory.
- *Auto Memory Mode*: Aetherius autonomously manages memory uploads.
- *Manual Memory Mode*: You decide when to upload memories.
- *Training Memory Mode*: Control memory uploads for each memory type.
- **Agent Mode**: Unleash Aetherius's research prowess and connect to external data sources.
- *Web DB*: Access web-scraped data effortlessly.
- *File DB*: Extract insights from various file formats.
- *Memory DB*: Efficiently search the most relevant memories.

------

### Current Tools

With Aetherius, you have an arsenal of tools to explore and use:

- **Web Scrape/Search**: Gather information from websites with ease.
- **File Processor**: Process a variety of file types for insights and knowledge.  The supported file types are: .epub, .pdf, .txt, .png, .jpg, .jpeg, .mp4, .mkv, .flv, and .av

------

Aetherius's development is self-funded by my day job, consider supporting me if you use it frequently, want development speed to increase, or if you want help setting up a custom version of Aetherius for your use case.

<a href='https://ko-fi.com/libraryofcelsus' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi3.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

------

[Aetherius Usage Guide](https://www.libraryofcelsus.com/research/aetherius-usage-guide/)

[Skip to installation guide](#installation-guide)

[Skip to Changelog](#changelog)

More output examples can be found at https://github.com/libraryofcelsus/Aetherius_Ai_Assistant_Outputs

------

Join the Discord for help or to get more in-depth information!

Discord Server: https://discord.gg/pb5zcNa7zE

Subscribe to my youtube for Video Tutorials: https://www.youtube.com/@LibraryofCelsus (Channel not Launched Yet)

Code Tutorials available at: https://www.libraryofcelsus.com/research/public/code-tutorials/

Made by: https://github.com/libraryofcelsus

Inspired by https://github.com/daveshap/

------

## Example
(Uses Llama2-Chat-13B and a webscrape of this Github page.)

![alt text](http://www.libraryofcelsus.com/wp-content/uploads/2023/08/Aetherius-Example-3.png)

## Database Visualization with Qdrant

![alt text](http://www.libraryofcelsus.com/wp-content/uploads/2023/08/Qdrant-Visulization.png)

## Agent Architecture

![alt text](http://www.libraryofcelsus.com/wp-content/uploads/2023/07/AetheriusArch.png)

## Future Plans

• Improve Ui

• Continue to Improve internal prompts

• Finish Aetherius Usage Guide

• Better Documentation 

• Book/File Summarizer Tool

• Data Comparison Tool

• Add more LLM models

• Launch Ai Tutorial YouTube Channel

# Changelog:
**0.045c**

• Added Sub-Agent script.  You can now create custom sub-agents for Aetherius's parallel processing loop.

• Converted Llama 2 Chatbot to use Json for settings.

• Better Sorting for using Multiple Hosts.

• Various Bug Fixes


**0.045c**

• Added Ability to use Multiple Hosts with Oobabooga.

• Improved Llama 2 Internal Prompts

• Added Important Score to some memory types (Still a work in progress)

**0.045b**

• Added Video Processing to the Llama 2 file scrape tool. 

• Added Voice Cloning with coqui TTS.

**0.045a**

• Added check for punctuation for memory uploads to avoid cut off uploads in Llama 2 chatbot.

• Added Delete buttons for external resources in DB management Deletion Menu in Llama 2 chatbot.

• Improved Internal Prompts for Llama 2 Agent Mode and Webscrape Tool.

• Various Bug Fixes

**0.044f**

• Added Voice input using Whisper and TTS using gTTS or Eleven Labs.  Bark TTS still a work in progress.

**0.044e**

• Fixed Bug where embedding size wasn't being set when creating collections.

• Switched usernames from collection name to metadata.

**0.044d**

• Added Embedding Selection Menu, for now only Sentence Transformers and Hugging Face Embeddings are available.

**0.044c**

•New Gui for Aetherius.  Most Chatbot modes are now consolidated under one Ui.

**0.044b**

•Updated Llama-2 Gui Appearance and Features

•Merged Fileprocessing Chatbot into Aethersearch

•Fixed Bug where html markdown was printed instead of normal text when using Public Api.

•Added Colab Notebook for people without a GPU.

**0.044a**

• Consolidated Collections for better visualization with Qdrant (Available in the Qdrant dashboard)

• Added Source tag for external data scrapes

**0.043**

• Converted to Qdrant.  Aetherius can now be ran 100% locally!

• Removed OpenAi and Pinecone Api key check from main menu and added it to the individual scripts.

• Cleaned up Llama 2 code

• Reworked Input Window, now handles larger text strings better.

• Updated OpenAi scripts, they should now follow the conversation track better.

• Added Delete Button to Edit Conversation in Llama 2 Chatbot

• Added Long Term Memory Upload in Llama 2 Chatbot

• Updated Delete Menu in DB Management in Llama 2 Chatbot

• Fixed Bug where only one Implicit and Explicit Memory were uploaded

• Improved Memory Prompts, works alot better with the 7B model of Llama 2 now.  Still wouldn't recommend using the 7B model though.

• Improved Auto Memory Upload.

• Various Bug Fixes

**0.042**

• Added GUI for Aetherius.  Very basic for now.

• Local Llama 2 update, works well, but still needs to be improved.

• Added Edit Conversation

• Added Model Selection

• Added GPT 3.5 Turbo 16k

• Added Webscrape Delete Button

• Small Webscrape prompt rework

• Various Bug Fixes

**0.041**

• Reworked Conversation History, it will now persist past shutdown.

• Added .TXT, .PDF, and .EPUB text extractors. For now it just functions similarly to the webscrape. Place file in the "Upload" folder in its extension's respective folder.  Then run "GPT_4_Text_Extractor.py" to extract all of the files, they will be moved to the "Finished" folder once done.

• Added Photo OCR to the Text Extractor.  To use, place the desired photo in the /Upload/SCANS folder.  Using this feature requires tesseract: https://github.com/UB-Mannheim/tesseract/wiki    Once installed, copy the "Tesseract-OCR" folder from Program Files to the "Aetherius_Ai_Assistant" Folder.  This will allow you to take Screenshots with the windows snipping tool and upload them to Aetherius for processing.

**0.04**

• New User System Implemented.  Change the username prompt in the config folder to change users.  This will allow you to have multiple versions of Aetherius on the same index.

• First iteration of Aether Search/Scrape implemented. This will be the eventual websearch system.  As of now it requires a Google CSE key and Google API key, other options coming soon.

• Autonomous Tasklist Generation

• Aetherius now decides for itself whether or not each task in its generated tasklist requires a websearch, memory search, or both.

• Switched to Username based DB to Bot Name based DB, will add user's again later.

• Re-added Users

• Various Bug Fixes

• Intuition Prompt Rework

• Various Bug Fixes

# Installation Guide

## Google Colab

To run Aetherius on Google Colab, first run the Oobabooga Public Api: <a target="_blank" href="https://colab.research.google.com/github/libraryofcelsus/Aetherius_AI_Assistant/blob/main/Colab%20Notebooks/Oobabooga_Public_Api.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>  

Then, go to Qdrant and get an API key and URL: https://qdrant.to/cloud

The final step will be to run the actual Aetherius Script.  You can install it locally or run it on a colab notebook found here: <a target="_blank" href="https://colab.research.google.com/github/libraryofcelsus/Aetherius_AI_Assistant/blob/main/Colab%20Notebooks/Aetherius_Colab_Edition_Oobabooga.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>   
(Note: The colab version of Aetherius is rarely updated and is more meant as a demo.)

## Installer bat

Install Python 3.10.6, Make sure you add it to PATH: **https://www.python.org/downloads/release/python-3106/**

Run the Installer Bat as admin, it is located at: https://github.com/libraryofcelsus/Aetherius_AI_Assistant/blob/main/scripts/resources/install.bat

(If you get an error when installing requirements run: **python -m pip cache purge**)

![alt text](http://www.libraryofcelsus.com/wp-content/uploads/2023/05/Capture11111111.png)

Copy your OpenAi and Qdrant API/URL keys to the api_keys folder inside of the created Aetherius_Ai_Assistant folder if you are using the OpenAi version.

Copy your Google CSE Key and Api Key to the api_keys folder or set Web_Search to False in the External Resources Sub-Agent.  You can also change the search engine to Bing.

To run Aetherius on Google Colab with Oobabooga using a public Api, use the Notebook file in the "./Colab Notebooks" Folder.  To use the Public Api with Aetherius, change the "Set Oobabooga Host" in the Config Menu to the given non-streaming Url. <a target="_blank" href="https://colab.research.google.com/github/libraryofcelsus/Aetherius_AI_Assistant/blob/main/Colab%20Notebooks/Oobabooga_Public_Api.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

To run Aetherius Locally using Oobabooga, first install the web-ui at: https://github.com/oobabooga/text-generation-webui

Then, under the "Interface Mode" tab, enable the api checkbox in both fields. Then click apply and restart the interface.

Next, navigate to the models tab. Uncheck the autoload models box and then input "TheBloke/Llama-2-13B-chat-GPTQ" into the downloads box (7B model can be used for faster results, but it occasionally breaks format and has a tendency to make things up.  Wouldn't recommend if you need factual data). Other models may work, but this is the one that is tested.

Once the download is completed, reload the model selection menu and then select the model. Change the model loader to Exllama and set the max_seq_len to "4096".  Set the "gpu_split" to 1 GB under your Gpu's max Vram.

Click the "load" button and load the model. The Aetherius should now work!

Qdrant Cloud: https://qdrant.to/cloud

To use a local Qdrant server, first install Docker: https://www.docker.com.  
Next type: **docker pull qdrant/qdrant:v1.5.1** in the command prompt.  
After it is finished downloading, type **docker run -p 6333:6333 qdrant/qdrant:v1.5.1**  

See: https://docs.docker.com/desktop/backup-and-restore/ for how to make backups.

Once the local Qdrant server is running, it should be auto detected by Aetherius.

If No Qdrant server is running, Aetherius will save to disk.

Launch Aetherius with **run.bat**

Upload heuristics to DB and change the Bot and User name to start chatting with Aetherius!  
Heuristic examples, and files to modify prompts can be found in the config folder.  Prompts can also be edited through the Config Menu.

Photo OCR (jpg, jpeg, png) requires tesseract: https://github.com/UB-Mannheim/tesseract/wiki
Once installed, copy the "Tesseract-OCR" folder from Program Files to the "Aetherius_Ai_Assistant" Folder.

 To get Whisper working with cuda, you may need to run the commands: **.\venv\Scripts\activate**  **pip uninstall torch torchaudio**    **pip install torch torchvision torchaudio -f https://download.pytorch.org/whl/cu118/torch_stable.html**

[Aetherius Usage Guide](https://www.libraryofcelsus.com/research/aetherius-usage-guide/)

## Windows Installation

**Guide with Photos can be found at [https://www.libraryofcelsus.com/aetherius-setup-guide/]**

**Photo Guide Out of Date**

1. Install Git: **https://git-scm.com/** (Git can be skipped by downloading the repo as a zip file under the green code button)

2. Install Python 3.10.6, Make sure you add it to PATH: **https://www.python.org/downloads/release/python-3106/**

3. Open the program "Git Bash". 

4. Run git clone: **git clone https://github.com/libraryofcelsus/Aetherius_AI_Assistant.git**

5. Open CMD as Admin (Command Panel)

6. Navigate to Project folder: **cd PATH_TO_AETHERIUS_INSTALL**

7. Create a virtual environment: **python -m venv venv**

8. Activate the environment: **.\venv\scripts\activate**   (This must be done before running Aetherius each time. The run.bat will also automatically do this.)

9. Install the required packages: **pip install -r requirements.txt**   
(If you get an error when installing requirements run: **python -m pip cache purge** after activating the venv)

10. Update Numpy version: **pip install --upgrade numpy==1.24**  (If you get an error from TTS ignore it.)

11. Install FFmpeg: **https://www.gyan.dev/ffmpeg/builds/**

12. Install Torch with Cuda: **pip uninstall torch torchvision**  **pip install torch torchvision torchaudio -f https://download.pytorch.org/whl/cu118/torch_stable.html**

13. Copy your OpenAI api key to key_openai.txt (If using Oobabooga, you may skip this.)

16. If using Qdrant Cloud copy their Api key and Url to their respective .txt files in the ./api_keys folder.  Qdrant Cloud: https://qdrant.to/cloud

17. To use a local Qdrant server, first install Docker: https://www.docker.com/

18. Now run: **docker pull qdrant/qdrant:v1.5.1** in CMD

19. Next run: **docker run -p 6333:6333 qdrant/qdrant:v1.5.1**

20. Once the local Qdrant server is running, it should be auto detected by Aetherius.  If No Qdrant server is running, Aetherius will save to disk.   
(See: https://docs.docker.com/desktop/backup-and-restore/ for how to make backups.)

21. Copy your Google Api key to key_google.txt  (You can disable the External Resources Web_Search in the script file.)

22. Copy your Google CSE ID to key_google_cse.txt

23. If you plan on using Photo OCR (jpg, jpeg, png Text Recognition), it requires tesseract: https://github.com/UB-Mannheim/tesseract/wiki
    Once installed, copy the "Tesseract-OCR" folder from Program Files to the "Aetherius_Ai_Assistant" Folder.  Photos must be placed in the ./Upload/SCANS folder.

24. Run main.py by typing **python main.py** in cmd or **run.bat** as admin to start Aetherius. (Using run.bat will let you skip opening CMD and activating the 
    environment.)

25. Select DB Upload Heuristics from the DB Management menu to upload Heuristics for the bot, this DB can also function as a Personality DB. An example of how to do 
    this can be found in "personality_db_input_examples.txt" in the config folder.

26. Edit the chatbot's prompts with the Config Menu. This will let you change the main, secondary, and greeting prompts.  You can also change things like the font style 
    and size.

27. You can change the botname and the username in the login menu.  Changing either of these will create a new chatbot.

28. Once the chatbot has adopted a desired personality, I recommend creating a backup of the "nexus" folder and then create a collection of the "aetherius" index on 
    pinecone.io.  This will let you revert back to a base state if issues arise later.

29. Once you have made a backup, you can start using the "Auto" mode, this mode has Aetherius decide for itself whether or not it should upload to its memories.

30. To run Aetherius Locally using Oobabooga, first install the web-ui at: https://github.com/oobabooga/text-generation-webui    
(To use Google Colab, use the Notebook file in the "./Colab Notebooks" Folder.  To use the Public Api with Aetherius, change the "Set Oobabooga Host" in the Config Menu to the given non-streaming Url.)  <a target="_blank" href="https://colab.research.google.com/github/libraryofcelsus/Aetherius_AI_Assistant/blob/main/Colab%20Notebooks/Oobabooga_Public_Api.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

31. Then, under the "Interface Mode" tab, enable the api checkbox in both fields.  Then click apply and restart the interface.

32. Next, navigate to the models tab. Uncheck the autoload models box and then input "TheBloke/Llama-2-13B-chat-GPTQ" into the downloads box. Other models may work, but this is the one that is tested.

33. Once the download is completed, reload the model selection menu and then select the model. Change the model loader to Exllama and set the max_seq_len to "4096". Set the "gpu_split" to .5 under your Gpu's max Vram.

34. Click the "load" button and load the model.  The Oobabooga API bots should now work!

-----

## About Me

In January 2023, I had my inaugural experience with ChatGPT 3.5 and LLMs in general. Since that moment, I've been deeply obsessed with AI, dedicating countless hours each day to studying it and to hands-on experimentation. The Aetherius AI Assistant is the culmination of that research.

# Contact
Discord: libraryofcelsus      -> Old Username Style: Celsus#0262

MEGA Chat: https://mega.nz/C!pmNmEIZQ

Email: libraryofcelsusofficial@gmail.com

