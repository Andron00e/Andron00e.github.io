---
title: Llama-LoRa Project
summary: My poject on parameter-efficient fine-tuning of LLMs.  More than 1000 downloads on HuggingFace.
tags:
  - Deep Learning
date: '2023-07-20'

links:
  - icon: hugging-face
    #icon_pack: fab
    #name: Follow
    url: https://huggingface.co/Andron00e/YetAnother_Open-Llama-3B-LoRA-OpenOrca
url_code: 'https://github.com/Andron00e/Llama-LoRA-project'
---
### Quality evaluation and results

* Fine-tuned on OpenOrca Open Llama 3B
  
|  Task   |Version | Metric |Value  |   |Stderr|
|---------|:------: |:--------|:-----: |:---:|:-----:|
|hellaswag|      0 |acc     |0.4899 |±  |0.0050|
|         |        |acc_norm|0.6506 |±  |0.0048|


* Fine-tuned on my custom dataset in russian language Open Llama 3B
  
|  Task   |Version| Metric |Value |   |Stderr|
|---------:|------:|--------|-----:|---|-----:|
|hellaswag|      0|acc     |0.4818|±  |0.0050|
|         |       |acc_norm|0.6377|±  |0.0048|


* Fine-tuned on mixed dataset (one part – Orca, second part – custom dataset)

|  Task   |Version| Metric |Value |   |Stderr|
|---------|------:|--------|-----:|---|-----:|
|hellaswag|      0|acc     |0.4618|±  |0.0050|
|         |       |acc_norm|0.6019|±  |0.0049|


* Fine-tuned on "wmt19", 'ru-en' dataset

|  Task   |Version| Metric |Value |   |Stderr|
|---------|------:|--------|-----:|---|-----:|
|hellaswag|      0|acc     |0.4817|±  |0.0050|
|         |       |acc_norm|0.6362|±  |0.0048|