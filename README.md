LangGraph Projects

Overview
This repository contains learning projects and experiments built with LangGraph and large language models.
Most work is captured in Jupyter notebooks so it is easy to follow and rerun.

Repository contents
- Notebooks for setup and examples
- Simple LangGraph workflows and state based graphs
- Prompt chaining and related experiments

Quick start
1 Install Python
2 Create and activate a virtual environment
3 Install packages
4 Create an env file with your API keys
5 Open the notebooks and run the cells

Example commands
python3 -m venv myenv
source myenv bin activate
python -m pip install -U pip
python -m pip install langgraph langchain python-dotenv

Environment variables
Create a file named env in the repository root and add your keys.
Do not commit this file.

Git and security
- Never commit secrets like API keys
- Never commit virtual environment folders
- The gitignore in this repo is configured to help with that

Suggested structure for new work
- Create one folder per project or topic
- Keep one notebook per lesson or experiment
- Add a short description and goal at the top of each notebook

Notes
If a notebook fails due to missing credentials check your env file and confirm the keys are available in the environment.

