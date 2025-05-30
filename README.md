# GenerativeAIResearch

A collection of various AI topics, technologies, related to AI Agents, Generative AI, and chatbots, including workflows, hackathons, and projects I've developed.


# Coding a repo within another repo:
- cd Generative-AI-Research/Github-Models

- Now clone the FORKED Azure repo into that subfolder
- Fork the original repo first, then clone your fork into this repo. 
- git clone https://github.com/YOUR_USERNAME/Azure-Samples/python-ai-agent-frameworks-demos
- cd python-ai-agent-frameworks-demos

- Create a python virtual environment like usual, including installing dependencies and running the appropriate scripts.

- Now instead of saving these changes directly within your parent repo (bad practice because we'll have a git rep within a git repo then), use submodules:
- cd Generative-AI-Research/Github-Models
- git submodule add https://github.com/YOUR_USERNAME/Azure-Samples/python-ai-agent-frameworks-demos
- git commit -m "Add Azure AI agent demo as submodule"
- git push

What does Submodules do in this case?
 - We're essentially embedding a pointer to another commit history in a separate repo, but we're accessing those files as if they are in this repo.
 - This ensures all of that git history doesn't get copied over to our parent repo here.
