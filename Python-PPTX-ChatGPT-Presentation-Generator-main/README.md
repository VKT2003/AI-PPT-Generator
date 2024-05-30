# Python-PPTX-ChatGPT-Presentation-Generator
## Overview

This is a tool to automatically generate PowerPoint presentations with OpenAI's gpt-3.5-turbo-0301 model (ChatGPT) and python-PPTX.

## TODO

- Model selection option
- Fix GUI freezing issues
- Create new directory for each presentation

## Setup

1. Install the following packages:
```
pip install openai
pip install icrawler
pip install python-pptx 
```
(for `icrawler`, you may also need to install `six` and `bs4` manually)

2. Download main.py
3. Make sure theme0.pptx is in the same directory as main.py
4. Run main.py
5. Input the information requested.

## OpenAI API Key

You will be prompted for an OpenAI API Key. You can find this at [https://platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys)

## Some Notes

- The images cralwed have a random name and will be stored at the root directory!
- The GUI may freeze when "Submit" is clicked. It will unfreeze once it is finished.
