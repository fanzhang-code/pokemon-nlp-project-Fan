This project explores domain-specific NLP using the Pokémon Trading Card Game (PTCG) dataset. The goal is to extract structured JSON information from semi-structured card descriptions using Large Language Models (LLMs).

The project compares:

Prompt engineering baseline
LoRA fine-tuning on Qwen2.5-1.5B-Instruct

Key features:

Dataset preprocessing and augmentation (fetch_pokemon_cards.ipynb)
PTCG text-to-JSON extraction (fine_tune_data_convert.ipynb)
LoRA fine-tuning with PEFT (tune.ipynb)
Baseline vs fine-tuned evaluation
JSON validity and accuracy metrics
