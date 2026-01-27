# 💬 Expert Chat
This notebook shows how to use Parameter-Efficient Fine-Tuning (PEFT) to train a Low-Rank Adaptation (LoRA) for a large language model as to make it more capable at talking about a specific subject. In this case the subject is "board games", to which purpose a data set is included with information, strategy and trivia about board games.

![banner](https://raw.githubusercontent.com/bshtmichielsen/expert_chat/refs/heads/main/BANNER.jpg)

*Image by Stable Diffusion: a machine explaining board games to children*

This notebook is intentionally designed as a foundational starting point and does not strictly adhere to established best practices as it is meant as a learning opportunity. This repo belongs to a five part course:&nbsp;&nbsp;&nbsp; 🏠&nbsp;[House&nbsp;Price&nbsp;Predictor](https://github.com/bshtmichielsen/house_price_predictor)&nbsp;&nbsp;&nbsp; 🐏&nbsp;[Animal&nbsp;Sound&nbsp;Identifier](https://github.com/bshtmichielsen/animal_sound_identifier)&nbsp; &nbsp;👗&nbsp;[Clothing&nbsp;Sorter](https://github.com/bshtmichielsen/clothing_sorter)&nbsp;&nbsp;&nbsp; 🍎&nbsp;[Fruit&nbsp;Detector](https://github.com/bshtmichielsen/expert_chat)&nbsp;&nbsp;&nbsp; 💬&nbsp;[Expert&nbsp;Chat](https://github.com/bshtmichielsen/expert_chat)&nbsp; Feel free to learn from the other parts too!

## 📚 Preparation
Please ensure that you are familiar with the following aspects in order to successfully work with this repo and notebook.
 - You can explain what a [Large Language Model](https://www.geeksforgeeks.org/artificial-intelligence/large-language-model-llm/) is.
 - You understand the conceptual idea of the [transformer](https://www.geeksforgeeks.org/machine-learning/getting-started-with-transformers/) architecture.
 - You know what [Parameter-Efficient Fine-Tuning](https://www.geeksforgeeks.org/artificial-intelligence/what-is-parameter-efficient-fine-tuning-peft/) is and can explain its advantages over traditional fine-tuning.
 - You understand what a [Low Rank Adaptation](https://www.geeksforgeeks.org/deep-learning/what-is-low-rank-adaptation-lora/) is and can explain its advantages/disadvantages and general inner workings.

## 🎯 Learning opportunities
The following aspects of machine learning are part of this example:
 - Reading Q&A text corpus from jsonl files
 - Training a LoRA for a large language model.

## 🤔 Considerations for improvement
The following is a list of considerations for improvement or for your own project.
 - The LoRA has a configuration that contains hyperparameters that strongly influence its effectiveness. The current values are a sensible default, but no investigation was done into other values.
 - It is notoriously hard to define a proper test metric for large language models. Imagine we want to add something anyway, what could be a reasonable metric. Can you implement it?

## ⭐ Citation & Star
If you use my work please cite and star ⭐ this repo. Thanks!

Michielsen, Bas S.H.T. (2026) "Expert Chat" GitHub: https://github.com/bshtmichielsen/expert_chat