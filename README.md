# GenAI LLMs with Hugging Face

This repository hosts tutorials, notebooks, and utilities for working with large-language models (LLMs) using Hugging Face Transformers. You’ll find everything from basic prompt engineering to advanced transfer-learning and fine-tuning workflows.

## What’s Inside

- Interactive notebooks to experiment with prompts, example tasks, and model outputs  
- PDF snapshots of lengthy or compute-intensive workflows (so you can review without re-training)  
- Helper scripts for data preparation, model training, evaluation, and prompt demos  
- A `requirements.txt` detailing all required Python packages  

> **Note:** PDFs are included for reference because GitHub does not render notebooks directly.

## Getting Started

1. Clone the repo  
   ```bash
   git clone https://github.com/kyramichel/GenAI---LLMs-HuggingFace.git
   cd GenAI---LLMs-HuggingFace
   ```

2. (Optional) Create & activate a virtual environment  
   ```bash
   python -m venv venv
   source venv/bin/activate      # Windows: venv\Scripts\activate
   ```

3. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

4. Set your Hugging Face token  
   ```bash
   export HUGGINGFACE_TOKEN="your_token_here"      # Windows: set HUGGINGFACE_TOKEN="your_token_here"
   ```

## How to Use

- **Run notebooks interactively:**  
  ```bash
  jupyter notebook
  ```
- **Browse PDFs** for step-by-step guides on complex or long-running processes  
- **Execute scripts** to preprocess data, fine-tune models, or test prompts  
  ```bash
  python scripts/train_model.py
  python scripts/prompt_demo.py
  ```

## Roadmap

- More advanced prompt-engineering patterns  
- Efficient fine-tuning techniques (LoRA, adapters)  
- Zero-shot and few-shot learning demos  
- Integration with retrieval-augmented generation (RAG)  
- Production deployment examples  

Contributions and suggestions are welcome—watch this space for new features and updates!
