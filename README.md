# 🧠 Generative AI Projects

Welcome to my collection of **basic generative AI projects**. This repository includes small but powerful experiments and demos built using cutting edge tools like **OpenAI**, **LangChain**, and more. These projects cover **text generation**, **chatbots**, **image generation**, and **API integrations**.

---

## 📁 Contents

| Project | Description |
|--------|-------------|
| **01-text-generator** | Simple app that generates paragraphs or stories using GPT-3.5 |
| **02-chatbot-basic** | A conversational chatbot using LangChain + OpenAI |
| **03-image-generator** | Generate AI images from text prompts (e.g. DALL·E) |
| **04-prompt-playground** | Experiments with different prompt engineering techniques |
| **05-api-integration** | Calling OpenAI APIs securely via Python (with `.env` setup) |

> 🔒 **No API keys are included** – please add your own via environment variables.

---

## 🚀 Getting Started

### 🛠️ Prerequisites

- Python 3.8+
- OpenAI account & API key
- Git

### 📦 Install Dependencies

```bash
pip install -r requirements.txt
```

### 🔐 Set Up Your API Key

**Option 1: Temporary (Colab or scripts)**

```python
import os
os.environ["OPENAI_API_KEY"] = "your-key-here"
```

**Option 2: `.env` File**

1. Create a file called `.env` in the project root:
    ```
    OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxx
    ```
2. Load it in your code:
    ```python
    from dotenv import load_dotenv
    load_dotenv()
    ```

---

## 💡 Why This Repo?

This repo is for:

- Learning and practicing AI concepts hands-on
- Building confidence with OpenAI's API
- Understanding prompt crafting and basic pipelines
- Showcasing your work in a clean and reusable way

---

## 📸 Screenshots

> Add images or Colab previews here if available.

---

## 🧠 Future Ideas

- Fine-tuning a model
- Multi-turn chat memory with LangChain
- Voice-to-text or text-to-speech integration
- LangGraph (multi-agent workflows)

---

## 🤝 Contributions

Feel free to fork and star ⭐ this repo!  
Pull requests are welcome for improvements or additional mini-projects.

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).
