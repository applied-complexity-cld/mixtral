# Mixtral-8x7B for Text Cleanup 🤗

This repository uses the HuggingFace's [Mixtral-8x7B-Instruct-v0.1](https://huggingface.co/mistralai/Mixtral-8x7B-Instruct-v0.1) LLM for summarising and cleanup of English speech transcripts. 

## Installation and set-up
We use a conda environment. To run the code in the repository, please run the following:

`conda env create -f -environment.yml`
`conda activate mixtral`


## Instruction format
The template used to build a prompt for the Instruct model is defined as follows:

`<s> [INST] Instruction [/INST] Model answer</s> [INST] Follow-up instruction [/INST]`

As suggested, we will use this template to prompt the model.