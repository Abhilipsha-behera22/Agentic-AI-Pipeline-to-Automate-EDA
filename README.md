# Agentic AI Pipeline to Automate EDA

##  Overview

This project builds an **Agentic AI pipeline** using LLMs to automate Exploratory Data Analysis (EDA).

Instead of manually writing analysis code, the system:

* Understands dataset schema
* Generates EDA code automatically
* Executes the code
* Produces insights like a data analyst



##  Architecture

1. **Coder Agent**

   * Generates Python EDA code using LLM (Mistral via Ollama)

2. **Execution Engine**

   * Runs generated code dynamically

3. **Analyst Agent**

   * Interprets statistical results
   * Provides investment insights

4. **Validation Layer**

   * Checks:

     * Code correctness
     * Hallucination
     * Schema alignment



## ⚙️ Tech Stack

* Python
* LangChain
* Ollama (Mistral LLM)
* Pandas, Matplotlib, Seaborn



## Dataset

* Stock Market Dataset (AAPL)



##  How to Run

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
2. Run notebook in Google Colab
3. Upload dataset
4. Execute all cells



## Key Features

* Fully automated EDA
* LLM-based code generation
* Self-validation pipeline
* Analyst-style insights



## Future Improvements

* Multi-dataset support
* UI dashboard
* Integration with real-time APIs
* Better hallucination control



##  Author

Abhilipsha Behera

