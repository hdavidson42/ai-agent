# Personal AI agent
**This was created for education and personal use. This agent has the ability to read, write to and overwrite files, and execute .py python files. Without robust security features I would not recommend using this on your personal machine**
![demo](https://files.catbox.moe/z0lvr6.gif)
## Description
This is an AI agent created using google gemini's API. It can take a prompt and use it's LLM to generate a text response. It also has the functions to:
- List files and directories
- Read file contents
- Execute Python files with optional arguments
- Write or overwrite files
## Motivation
With the rapid rise of large language models like ChatGPT and Google Gemini becoming embedded in everyday tools and workflows, I was inspired to explore how these systems work and what it takes to build a personal AI agent.
This project was created as a hands-on learning experience to better understand the integration of LLMs into real-world applications. 
By enabling the agent to read, write, and execute Python files, I aimed to experiment with the practical utility and limitations of AI in a local environment; while also acknowledging the importance of security when giving such systems access to sensitive operations.
## Usage
python3 main.py {PROMPT} [--verbose]

execute the python file as normal
python3 main.py 
the next argument will then be the prompt you wish to give the agent. There is an aditional argument --verbose which you can use to also provide additonal information such as the function name being called and the amount of tokens being sent to and recieved from the AI.
