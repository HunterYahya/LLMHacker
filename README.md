Emulating a Hacking LLM utilizing the free API key that you can generate on openrouter.ai 
I choose the DeepSeek V3 0324 (FREE) Model but you can replace it in the python code with any model that you want basically. 
You should put in your free API Key and Model type in the lines between 61 and 67 in the .py file, it is very very simple to do. 
After that you need to do the following, make sure you have Python installed. I suggest using VS Code for this whole process actually. 

Using Git Bash (easiest option):

Open Git Bash terminal in VS Code
Create virtual environment:
python -m venv venv

Activate it (using Git Bash syntax):
source venv/Scripts/activate

Install required packages:
pip install streamlit requests

Run the app:
llmhacker.py

requests is also a needed Python package so make sure to pip install that along with streamlit. run the .py file and you're good to go with your Hacking Assistant! 

This is my first ever Github little project so I would appreciate any feedback, improvements, or comments. 
