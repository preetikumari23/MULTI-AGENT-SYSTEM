\# Multi-Agent Research System



An AI-powered research assistant built using LangChain and multiple specialized agents that collaborate to search, analyze, and summarize information from the web.



\## Project Overview



The Multi-Agent Research System demonstrates how autonomous AI agents can work together to perform complex research tasks. Instead of relying on a single model call, the system divides responsibilities among multiple agents, creating a more structured and scalable workflow.



This project showcases practical applications of Generative AI, Agentic AI, Prompt Engineering, and Information Retrieval.



\## Key Features



\* Multi-agent architecture

\* Automated web research workflow

\* Real-time information retrieval

\* Content extraction and processing

\* Structured research output generation

\* Modular and extensible design

\* Environment variable management using python-dotenv



\## Architecture



User Query

↓

Research Agent

↓

Web Search Tool (Tavily)

↓

Content Extraction (BeautifulSoup)

↓

Analysis Agent

↓

Final Research Report



\## Tech Stack



\### Programming Language



\* Python



\### AI \& Agent Frameworks



\* LangChain



\### Search \& Retrieval



\* Tavily Search API



\### Web Processing



\* BeautifulSoup4

\* Requests



\### Utilities



\* Python Dotenv

\* Rich



\## Project Structure



```text

MULTI-AGENT-SYSTEM/

│

├── agents.py          # AI agent definitions

├── app.py             # Main application entry point

├── pipeline.py        # Multi-agent workflow orchestration

├── tools.py           # Search and utility tools

├── requirements.txt   # Project dependencies

├── README.md

└── .gitignore

```



\## Installation



\### Clone Repository



```bash

git clone https://github.com/preetikumari23/MULTI-AGENT-SYSTEM.git

cd MULTI-AGENT-SYSTEM

```



\### Create Virtual Environment



```bash

python -m venv .venv

```



\### Activate Environment



Windows:



```bash

.venv\\Scripts\\activate

```



Linux/Mac:



```bash

source .venv/bin/activate

```



\### Install Dependencies



```bash

pip install -r requirements.txt

```



\## Environment Variables



Create a `.env` file:



```env

TAVILY\_API\_KEY=your\_api\_key\_here

```



\## Running the Project



```bash

python app.py

```



\## Skills Demonstrated



\* Agentic AI Development

\* Large Language Model Integration

\* LangChain Framework

\* Information Retrieval Systems

\* API Integration

\* Prompt Engineering

\* Python Development

\* Modular Software Design

\* Research Automation



\## Potential Enhancements



\* Memory-enabled agents

\* Streamlit web interface

\* Vector database integration

\* Retrieval-Augmented Generation (RAG)

\* PDF report generation

\* Multi-modal research capabilities

\* Agent monitoring and evaluation dashboard



\## Why This Project Matters



Traditional AI applications rely on a single model response. This project demonstrates a modern agent-based approach where specialized AI agents collaborate to solve research tasks more effectively. It highlights concepts increasingly used in production AI systems and enterprise GenAI applications.



\## Author



Preeti Kumari



GitHub: https://github.com/preetikumari23



\## License



MIT License



