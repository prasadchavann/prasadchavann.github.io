---
title: "LLm Finetune - Task: Roleplay"
excerpt: "Aimed at helping people who feel alone, this project fine-tunes a Large Language Model (LLM) to simulate engaging roleplay conversations.<br/><br/><img src='/images/project_llmFinetune.png'>"
collection: portfolio
---

Aimed at helping people who feel alone, this project fine-tunes a Large Language Model (LLM) to simulate engaging roleplay conversations. By training the model to adapt to various roles, it creates meaningful and supportive chats, offering enjoyment and interaction for those in need.

### Technologies used:
- Python
- Tensorflow
- Hermes-Llama-8B model (HF)
- qLora technique
- Gradio for chatUI

### Approach:
- For dataset creation I've used character datasets from [DippyAI’s](https://huggingface.co/datasets/DippyAI/dippy_character_codex) Hugging Face collection.
- Created dialogue conversations for each character and saved them in a CSV file.
- Applied **Chatml** chat template to the dataset, then tokenized it for training.
- Fine-tuned the Hermes 8B model on [Lightning AI](https://lightning.ai/) using an L40s GPU with 48GB VRAM.
- Merged the PEFT model with the initial model.
- Tested model for various scores.
- Ran inference on the model to generate roleplay dialogues.

### Scores of model:
```bash
final_model_size_score 0.456667436785295
final_latency_score 0.806556841452
final_vibe_score 0.5322963908784612
coherence_score: 0.972652656523879
eval_model_size_score: 0.9276731246047549
creativity_score=0.8259571710556718
final_eval_score: 0.3133957153333748
```

### Skills I Gained:
- Tensorflow
- Quantization techniques
- Finetuning LLM
- Merging models
- Building inference and gradio UI

### Link to code:
[Download File](/files/fineTune.ipynb)<br/> 
[Dataset](/files/data_gen2_updated.csv)

### Model link:
[Ahanaas/HermesWithYou_V3](https://huggingface.co/Ahanaas/HermesWithYou_V3)

### Feel free to contribute :)
