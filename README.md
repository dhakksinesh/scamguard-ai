## ScamGuard AI

ScamGuard AI is an AI-powered app that detects whether a message is a scam or legitimate. It uses ReAct prompting with Google Gemini LLM to analyze text, provide reasoning, and generate a confidence score.


## Project Overview

Online scams are increasing across messaging platforms, emails, and social media. ScamGuard AI helps users quickly evaluate suspicious messages using Large Language Model reasoning.

The system applies the ReAct (Reasoning + Acting) prompting technique with Google Gemini to:

- Analyze message content
- Identify scam indicators
- Provide step-by-step AI reasoning
- Output a scam/legitimate classification with confidence score


## Key Features

- Scam Classification – Detects whether a message is a scam or not
- AI Reasoning – Uses ReAct prompting to explain why a message is classified
- Confidence Score – Provides a confidence level for each prediction
- Batch Processing – Analyze multiple messages at once
- CSV Upload Support – Upload CSV files for bulk analysis
- Interactive UI – Built with Streamlit for easy use


## Tech Stack

- Python
- Streamlit
- Google Gemini API
- ReAct Prompting Technique

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/scamguard-ai.git
cd scamguard-ai
```

### 2. Create a Virtual Environment (Recommended)
```bash
python -m venv venv
```

Activate the environment:

**Windows**
```bash
venv\Scripts\activate
```

**Mac/Linux**
```bash
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Set Up Environment Variables

Create a .env file and add your Gemini API key:
```bash
GEMINI_API_KEY=your_api_key_here
```

### 5. Run the Application
 ```bash
streamlit run app.py
```

The app will open in your browser.

## Demo
![ScamGuard AI Demo](assets/demo.gif)
