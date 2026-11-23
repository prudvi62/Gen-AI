# Gen-AI Lab Assignments

Repository containing lab assignments for Gen-AI.

## Directory Structure

```
├── Lab/
│   ├── Week1_LLM_call/          # Introduction to LLM calls (Gemini API)
│   ├── Week2_LLM_call/          # Provider abstraction (Gemini & Ollama)
│   ├── Week3_LLM_Call/          # Token usage logging with MongoDB
│   ├── Week4_LLM_Call/          # Tokenizer comparison (BPE, WordPiece, SentencePiece)
│   └── Week5_LLM_Call/          # Token economics & budget validation
├── .gitignore
└── README.md
```

## Setup Instructions

1. **Create and activate a virtual environment:**
   ```bash
   python -m venv .venv
   # On Windows:
   .venv\Scripts\activate
   # On macOS/Linux:
   source .venv/bin/activate
   ```

2. **Install requirements for each lab:**
   Navigate into any week's directory and run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables:**
   Copy `.env.example` to `.env` in the respective lab folder and add your API keys:
   ```bash
   cp .env.example .env
   ```
