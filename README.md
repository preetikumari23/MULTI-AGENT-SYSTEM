\# Multi-Agent Research System



A Python-based AI-powered research system that uses multiple agents to search, analyze, and summarize information from the web.



\## Overview



This project demonstrates how multiple AI agents can collaborate to perform research tasks. Each agent has a specific responsibility, such as searching for information, extracting relevant content, analyzing findings, and generating structured outputs.



\## Features



\- Multi-agent architecture

\- Web search integration using Tavily

\- Content extraction using BeautifulSoup

\- Automated research workflow

\- Modular and extensible design

\- Environment variable support with python-dotenv



\## Project Structure



```text

MULTI-AGENT-SYSTEM/

│

├── agents.py          # Agent definitions

├── app.py             # Main application

├── pipeline.py        # Research workflow pipeline

├── tools.py           # Search and utility tools

├── requirements.txt   # Dependencies

├── tree.txt           # Project structure

└── .gitignore

```



\## Technologies Used



\- Python

\- LangChain

\- Tavily Search API

\- BeautifulSoup4

\- Python Dotenv

\- Rich



\## Installation



\### Clone the Repository



```bash

git clone https://github.com/preetikumari23/MULTI-AGENT-SYSTEM.git

cd MULTI-AGENT-SYSTEM

```



\### Create Virtual Environment



```bash

python -m venv .venv

```



\### Activate Virtual Environment



\*\*Windows\*\*



```bash

.venv\\Scripts\\activate

```



\*\*Linux / Mac\*\*



```bash

source .venv/bin/activate

```



\### Install Dependencies



```bash

pip install -r requirements.txt

```



\## Environment Variables



Create a `.env` file in the project root directory:



```env

TAVILY\_API\_KEY=your\_tavily\_api\_key

```



\## Run the Application



```bash

python app.py

```



\## Workflow



1\. User enters a research topic.

2\. Search Agent gathers information from the web.

3\. Analysis Agent processes and evaluates the data.

4\. The system generates organized research findings.

5\. Results are displayed to the user.



\## Future Improvements



\- Memory-enabled agents

\- PDF report generation

\- Streamlit web interface

\- Vector database integration

\- Advanced RAG pipeline

\- Multi-modal research capabilities



\## Author



\*\*Preeti Kumari\*\*



GitHub: https://github.com/preetikumari23



\## License



This project is licensed under the MIT License.

