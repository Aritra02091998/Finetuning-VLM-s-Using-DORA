# Finetuning-VLM-s-Using-DORA

The paper proposes DoRA (Weight-Decomposed Low-Rank Adaptation) as a more efficient method for parameter-efficient fine-tuning (PEFT) of large models, such as LLaMA or VL-BART, particularly after LORA. It aims to bridge the gap between full fine-tuning (FT) and LoRA, improving performance without extra inference costs. So far, the public implementation of DORA with 4-bit Quantization (QDPRA) hardly exists for VLMs. Hence, I have created these notebooks to fine-tune small VLMs on VQA tasks using QDORA (4-bit).

Bare-minimum environment setup:

bitsandbytes              0.45.0                   pypi_0    pypi
datasets                  3.3.2            py39h06a4308_0
torchtriton               3.1.0                      py39    pytorch
torchvision               0.20.1               py39_cu118    pytorch
peft                      0.14.0                   pypi_0    pypi
pytorch                   2.5.1           py3.9_cuda11.8_cudnn9.1.0_0    pytorch
flash-attn                2.7.2.post1              pypi_0    pypi


![image](https://github.com/user-attachments/assets/ce8dd67c-9498-466b-9b18-da4ed62a99ae)
