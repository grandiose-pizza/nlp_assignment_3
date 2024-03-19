# NLP Challenge for Core42 AI Modelling team

## Goal
Finetune a model using peft adapters.
You may use any python library like transformers and/or bits&bytes etc.
PEFT offers parameter-efficient training methods. This method relies on a method called Low Rank Adaptoers (LoRA). Instead of fine-tuning the entire model you just have to fine-tune these adapters and load them properly inside the model.

Please use a small dataset like []"Abirate/english_quotes"](https://huggingface.co/datasets/Abirate/english_quotes) to finetune on a small model like []"facebook/opt-125m"](https://huggingface.co/facebook/opt-125m).

## Format Requirements
- Fork or clone this repo
- Maintain the directory structure given for the project
- Use Python 3.7+
- If you need additional imports specify them in `requirements.txt`

## Model Requirements
- Model should be trained on the given dataset.
- Create a model artifact and save it under `/models`.
- Report accuracy on `test`.


## API Requirements
- Serve the model as a REST API using FastAPI
- Be able to use CURL to send in text input and return the prediction.

## Data
The dataset you will be using contains ~2.51K rows of English quotes with author and tags. You need to finetune the base model to generate quotes.

You can split the Dataset into two splits `train` and `test`.


## Submission
Timebox this challenge to 8-10 hours. After completing the assignment, please compress whole repo and send it.
