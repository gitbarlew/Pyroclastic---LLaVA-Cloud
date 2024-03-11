# Pyroclastic - LLaVA Cloud
This repository contains files created to support the article titled "Running open AI models for free in under 10 minutes with a Google Colab and no extra accounts? Yes, Please!":
https://medium.com/@bartek.lewicz/running-open-ai-models-for-free-in-under-10-minutes-with-a-google-colab-and-no-extra-accounts-yes-4d38b59f0153

The article explores deploying and running a multimodal LLM AI model in the cloud using Google Colab's free tier, with no additional accounts required. It also demonstrates making the model's API accessible for experimentation and development on the web using Localtunnel.

## Files Included
Pyroclastic_Run_LLaVA_on_Google_Colab.ipynb: This notebook provides step-by-step instructions to deploy and run the LLaVA model on Google Colab's free tier. It includes code blocks for installing Ollama, downloading the LLaVA model, configuring runtime settings, launching Localtunnel, and validating the Ollama server's functionality.

LLaVA_Query_Example.ipynb: This notebook demonstrates how to interact with the deployed LLaVA model using Python scripts. It includes code blocks for installing the Ollama Python API and sending prompts and images to the model via the Ollama API.

Pyroclastic_diagram.ipynb: This notebook contains diagrams illustrating the workflow and architecture described in the article. It provides visual aids to better understand the deployment process and interaction with the LLaVA model.

## Usage
To use these notebooks, follow the instructions provided in the article. Make sure to have access to a Google account for running notebooks in Colaboratory (Colab) and install the necessary dependencies as mentioned in the notebooks.

### References
Localtunnel GitHub repository: https://github.com/localtunnel/localtunnel
Ollama homepage: https://ollama.com/
Ollama LLaVA Library: https://ollama.com/library/llava:v1.6
LLaVA GitHub repository: https://llava-vl.github.io/

### Author
Bartlomiej Lewicz

### License
This project is licensed under the Apache License 2.0.
