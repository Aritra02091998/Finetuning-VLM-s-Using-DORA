# Finetuning-VLM-s-Using-DORA

The paper proposes DoRA (Weight-Decomposed Low-Rank Adaptation) as a more efficient method for parameter-efficient fine-tuning (PEFT) of large models, such as LLaMA or VL-BART, particularly after LORA. It aims to bridge the gap between full fine-tuning (FT) and LoRA, improving performance without extra inference costs. So far, the public implementation of DORA with 4-bit Quantization (QDPRA) hardly exists for VLMs. Hence, I have created these notebooks to fine-tune small VLMs on VQA tasks using QDORA (4-bit).


![image](https://github.com/user-attachments/assets/ce8dd67c-9498-466b-9b18-da4ed62a99ae)
