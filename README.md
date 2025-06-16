# SmartInsight-AI
Streamlit app for AI-driven data insights.


Developing an AI assistant using **Streamlit** and **LangChain**, designed to help you with your data science projects. This AI assistant will streamline the entire process of a data science project, including:

- 🧪 Exploratory Data Analysis (EDA)
- 📈 Model Selection and Prediction
- 💬 Application Enhancement with Chatbox

---

## 🚀 Key Learnings

### 📦 Streamlit Features
- Structuring with titles, headings, and captions
- File upload & sidebar interaction
- Expanders for collapsible content
- Graph display for data visualization
- Text input, session state, caching, and non-stateful buttons

### 🧠 OpenAI & LangChain
- OpenAI key configuration & LLM usage
- Pandas Agent to:
  - Answer questions about the whole DataFrame
  - Respond to queries about selected variables
  - Answer custom user-defined queries

---

## ✏️ Knowledge Prerequisites

Basic understanding of:
- Data Science concepts (DataFrames, EDA, visualization)
- Python programming (syntax, libraries like pandas)
- Statistics (mean, median, std deviation, correlation)

> Don’t worry if you’re a beginner — the assistant is here to guide you!

---

## 🧰 Technology Stack

- **Streamlit**: Frontend for UI, file upload, interaction
- **OpenAI GPT**: Language model backend
- **LangChain**: Agent and prompt management for AI communication

---

## 🧪 Installation Guide

1. **Clone the repo**
```
git clone https://github.com/your-username/ai-data-assistant.git
cd ai-data-assistant
```

2. **Install dependencies**
```
pip install -r requirements.txt
```

3. **Set your OpenAI API key**
Create a file `apikey.py` and add:
```python
apikey = "your_openai_api_key_here"
```

4. **Run the Streamlit app**
```
streamlit run app.py
```

---

## 🧠 About Streamlit

Streamlit is an open-source Python library for building interactive web apps with minimal code. It supports:
- Rapid prototyping with Python
- Interactive widgets like sliders and buttons
- Seamless integration with pandas, matplotlib
- Easy deployment and sharing

> Learn more at [Streamlit.io](https://streamlit.io)

---

## 🔗 OpenAI and LLMs

OpenAI’s Large Language Models (LLMs) enable natural language understanding and generation. In this project, they help:
- Understand user input as questions
- Return insights from datasets using LangChain’s Pandas agent

> You can use GPT-3.5 or other models with your API key

---

## ⛓️ LangChain Capabilities

LangChain components used:
- **Models**: NLP backends (e.g., GPT)
- **Agents**: Handle user input and orchestrate tasks
- **Prompt Templates**: Create structured queries
- **Chains**: Combine actions together
- **Memory**: Maintain conversation context
- **Indexes**: Organize and retrieve document data

---

## 🧾 Sample Code Structure

```python
import os
from apikey import apikey
import streamlit as st
import pandas as pd
from langchain.llms import OpenAI
from langchain.agents import create_pandas_dataframe_agent
```

---

## 📂 Project Structure

```
ai-data-assistant/
├── app.py
├── apikey.py
├── requirements.txt
├── README.md
└── .env (optional)
```

---

## 💡 Final Thoughts

This project offers a hands-on learning opportunity in applied AI, natural language interfaces, and data science automation.

Whether you're a beginner or experienced, this AI Assistant helps bridge the gap between raw data and actionable insights.

---

© 2025 
