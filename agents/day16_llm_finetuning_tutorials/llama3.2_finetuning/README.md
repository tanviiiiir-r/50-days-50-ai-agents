# 🦙 Finetune Llama 3.2 in 30 Lines of Python ⚡

## 💡 Problem

Fine-tuning large models like Llama 3.2 can be complex and resource-intensive. Users need an efficient, straightforward way to adapt the model to specific datasets without requiring extensive computational resources.

## 🚀 Solution

This script demonstrates how to finetune the Llama 3.2 model using the Unsloth library with LoRA for parameter-efficient training. It is simple, fast, and can run on free Google Colab GPUs, making it accessible for research and experimentation.

## ⚙️ Features

* Finetunes Llama 3.2 using Unsloth
* Implements Low-Rank Adaptation (LoRA) for efficient fine-tuning
* Uses FineTome-100k dataset for multi-turn chat training
* Configurable for different model sizes (1B and 3B)
* Easy to run in Google Colab

## 🧠 Tech Stack

* Python 3.10+
* Unsloth library
* Transformers
* TRL (SFTTrainer)
* FineTome-100k dataset
* Google Colab GPU support

## 🧩 Setup Instructions

### Installation

```bash
# Clone the repository
git clone https://github.com/tanviiiiir-r/50-days-50-ai-agents.git
cd 50-days-50-ai-agents/agents/day16_llm_finetuning_tutorials/llama3.2_finetuning

# Install dependencies
pip install -r requirements.txt
```

### Run Instructions

```bash
python finetune_llama3.2.py
```

The finetuned model will be saved to the `finetuned_model` directory.

### Configuration

* `model_name`: Choose model (e.g., `unsloth/Llama-3.1-1B-Instruct`)
* `max_seq_length`: Set maximum sequence length
* `r`: LoRA rank
* Adjust training hyperparameters in `TrainingArguments`

### Customization

* Replace `load_dataset` call to use a different dataset
* Modify `target_modules` to finetune different layers
* Change chat template in `get_chat_template` for different conversational formats

### Running on Google Colab

1. Open a new Colab notebook
2. Install required libraries:

```
!pip install torch transformers datasets trl unsloth
```

3. Copy and run the script

## 🧭 Real-World Use Cases

* Efficiently adapt Llama 3.2 for domain-specific chatbots
* Rapid experimentation on conversational datasets
* Low-resource fine-tuning for research purposes
* Prototyping AI assistants or support agents

## 📁 Repository Info

* **Project Name:** Finetune Llama 3.2
* **Day Number:** 17
* **Series Name:** 50 Days, 50 AI Agents
* **Author:** [Md Tanvir Rana](https://github.com/tanviiiiir-r)
* **Tech Stack:** Python, Unsloth, Transformers, TRL, Google Colab
* **License:** MIT
