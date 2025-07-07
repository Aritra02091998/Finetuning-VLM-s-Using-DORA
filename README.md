# Finetuning-VLM-s-Using-DORA

The paper proposes DoRA (Weight-Decomposed Low-Rank Adaptation) as a more efficient method for parameter-efficient fine-tuning (PEFT) of large models, such as LLaMA or VL-BART, particularly after LORA. It aims to bridge the gap between full fine-tuning (FT) and LoRA, improving performance without extra inference costs. So far, the public implementation of DORA exists for LLMs. Hence, I have created these notebooks to fine-tune small VLMs on VQA tasks using DORA.
