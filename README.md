# Fine-tuning-GPT2 + QLoRA Llama 3.1 8B

The goal is to finetune GPT-2 (124M) and QLoRA finetune Llama 3.1 (8B) with a single GPU (T4 or L4) on Google Colab. First I trained the models on a Shakespear text for educational purposes then I finetuned a Llama 3.1 (8B) on my real dataset that I created using reverse engineering with ChatGPT (4o). I Added a GPT3.5-Turbo finetuning job afterwards to compare.

Results : (QLoRA) Llama 3.1 (8B) and (OpenAI FT-API) GPT3.5-Turbo seems to get similar results (validation loss around 0.8) for a training job of around 100 steps (~10 minutes).