# 🦥 Finetune Gemma 3 with Unsloth (4-bit LoRA) ⚡

## 💡 Problem

Fine-tuning large language models like Gemma 3 can be resource-intensive and complex. Many users lack access to full GPU resources for full model fine-tuning and need a parameter-efficient, simple approach.

## 🚀 Solution

This minimal example demonstrates how to finetune Google's Gemma 3 Instruct models using Unsloth with 4-bit loading and LoRA adapters. The setup is lightweight, readable, and runs on a CUDA GPU, enabling efficient fine-tuning of multi-turn chat datasets without the overhead of full model training.

## ⚙️ Features

* Supports Gemma 3 models: 270M, 1B, 4B, 12B, 27B
* Uses FineTome-100k dataset (ShareGPT-style multi-turn chats)
* Parameter-efficient LoRA adapters instead of full fine-tuning
* 4-bit quantization for memory-efficient training
* Simple, readable script with customizable training settings

## 🧠 Tech Stack

* Python 3.10+
* Unsloth library and `unsloth_zoo`
* TRL (Transformers Reinforcement Learning) `SFTTrainer`
* CUDA GPU support for 4-bit/8-bit quantization

## 🧩 Setup Instructions

### Installation

```bash
pip install -r requirements.txt
# Or upgrade to latest Unsloth per their guidance
pip install --upgrade --force-reinstall --no-cache-dir unsloth unsloth_zoo
```

### Run Instructions

```bash
python finetune_gemma3.py
```

Finetuned weights are saved to `finetuned_model/`.

### Configuration

Edit the top of `finetune_gemma3.py` to change:

* `MODEL_NAME` (e.g., `unsloth/gemma-3-270m-it`, `unsloth/gemma-3-1b-it`)
* `MAX_SEQ_LEN`, `LOAD_IN_4BIT`, `FULL_FINETUNING`

> Note: 4-bit/8-bit loading requires a CUDA GPU. On Mac (M1/M2), use CPU/MPS or a GPU machine.

## 🧭 Real-World Use Cases

* Quick fine-tuning of Gemma 3 for specific domains or tasks
* Research experiments with low-resource setups
* Adapting large models to multi-turn chat formats
* Efficient prototype creation for AI assistants or chatbots

## 📁 Repository Info

* **Project Name:** Finetune Gemma 3 with Unsloth
* **Day Number:** 16
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Unsloth, TRL, CUDA
* **License:** MIT

## References

* [Unsloth Gemma 3 Notes](https://unsloth.ai/blog/gemma3)
