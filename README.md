# Copywriting+ AI Agent

## 🚀 Overview

Copywriting+ is an intelligent AI agent built using LangGraph that revolutionizes content creation for marketers, copywriters, and content professionals. Born from the Google Gen AI Capstone project, this agent streamlines the entire copywriting workflow by combining cutting-edge LLM technology with powerful evaluation metrics and market research capabilities.

## ✨ Features

- **Immediate Content Generation**: Create high-quality copy 10x faster than traditional methods
- **Multiple Copy Variations**: Generate various styles (Problem-Solution, Storytelling, Data-Driven, etc.) from a single prompt
- **Performance Analytics**: Built-in evaluation metrics to measure hook strength, conversion potential, and overall quality
- **Market Research Integration**: Leverages real-time search to incorporate market trends and competitive insights
- **Modular Architecture**: Fully customizable pipeline that mirrors professional copywriting workflow

## 💡 How It Works

The Copywriting+ agent uses a modular architecture built on LangGraph:

1. **Analyzer**: Breaks down user requirements and extracts key details
2. **Market Researcher**: Gathers real-time market trends and competitive insights
3. **Copywriter**: Generates multiple copy variations based on requirements and research
4. **Evaluator**: Scores the generated copies on multiple dimensions
5. **Formatter**: Presents results in a comprehensive, easy-to-review format

## 🧩 Technical Architecture

The system is built using:
- **LangGraph**: For orchestrating the multi-agent workflow
- **Gemini**: Powers the core generative capabilities
- **Tavily Search**: For market research and trend analysis
- **Pandas**: For data processing and analysis

## 🛠️ Installation

```bash
pip install -qU 'langgraph>=0.3.21' 'langchain-google-genai>=2.1.2' 'langgraph-prebuilt>=0.1.7' 'langchain_community'
```

## 🔧 Configuration
You'll need to set up the following API keys:

**GOOGLE_API_KEY**: For accessing Google's Gemini models
**TAVILY_API_KEY**: For market research functionality


## 👥 Contributors

[Tan Fu Long] - Creator and Developer

## 🙏 Acknowledgements

Google Gen AI Intensive Capstone program
The LangChain and LangGraph teams for their excellent frameworks
