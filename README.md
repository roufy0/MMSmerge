# MSS AI Financial Analyzer 

An AI-powered financial analysis tool that combines traditional ratio calculations with large language models (LLMs) to generate comprehensive insights and recommendations for businesses.

##  Features

-  Calculates key financial ratios:
  - Current Ratio
  - Quick Ratio
  - Return on Equity (ROE)
  - Return on Assets (ROA)
-  Evaluates financial health using common benchmarks
-  Uses LangChain + LLaMA 3 to generate:
  - Human-readable reports
  - Strategic recommendations
  - Risk assessments

##  Tech Stack

- Python
- LangChain
- Ollama with LLaMA 3
- Jupyter Notebook

##  How It Works

1. The user is prompted to enter basic financial values (assets, liabilities, etc.).
2. The app computes standard financial ratios and evaluates them.
3. Results are fed into a LangChain prompt template.
4. The LLM (LLaMA 3) generates a detailed analysis and suggestions.

##  Installation

Clone the repository and install required packages:

```bash
git clone https://github.com/your-user/MSSProject.git
cd MSSProject
pip install langchain langchain-core langchain-community
