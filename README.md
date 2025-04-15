[![Company](https://images.crunchbase.com/image/upload/c_lpad,h_200,w_450,f_auto,q_auto:eco,dpr_1/t1zjaxp5qqcypqkcgooi)](https://www.linkedin.com/company/llumoai)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-follow-blue)](https://www.linkedin.com/company/llumoai)

# AI-Agents-RAG-Recipes

Practical AI recipes for building intelligent agentic workflows and optimizing RAG-based LLM applications.

Hey there! Welcome to this collection of advanced and agentic Retrieval-Augmented Generation (RAG) techniques. If you're working with Large Language Models (LLMs) and want to enhance their accuracy and relevance, you're in the right place!

### 🌟 Why RAG?

LLMs are great, but they have limitations—they rely on static training data and can sometimes make things up (a.k.a. "hallucinations"). Instead of constantly retraining models, RAG allows us to dynamically retrieve relevant, up-to-date information from external sources. That means smarter, more reliable AI responses!

This repo simplifies the process by offering ready-to-use implementations and guidance on evaluating their performance.

---

## 🔍 How Does RAG Work?

Think of RAG as a four-step process:

1️⃣ **Indexing** – Breaks down documents into chunks and stores them in an efficient way (usually as embeddings in a vector database).
2️⃣ **Retrieving** – Finds the most relevant documents based on a user’s query.
3️⃣ **Augmenting** – Adds this retrieved information to the query, giving the LLM extra context.
4️⃣ **Generating** – Produces a final, well-informed response.

With this setup, your AI system isn’t just guessing—it’s actually using external knowledge to generate answers.

---

## 📊 Why Evaluation Matters

Not all RAG implementations are equal! Evaluating RAG applications ensures that the retrieval and generation work together smoothly. Proper evaluation helps refine your model, making sure it delivers useful and trustworthy results in real-world applications like chatbots, summarization tools, and question-answering systems.

---

## ⚙️ Advanced RAG Techniques

This repo covers a variety of ways to make RAG even better. Some techniques focus on **improving search accuracy** (like hybrid approaches), while others help with **structuring retrieved information** before passing it to an LLM. The goal? Less fluff, more relevant answers!

Some advanced techniques you’ll find here include:

- **Hybrid RAG** – Combines different search strategies for better results.
- **HyDE (Hypothetical Document Embeddings)** – Generates example responses to improve retrieval.
- **Contextual RAG** – Filters unnecessary details to keep responses concise.
- **RAG Fusion** – Ranks and merges multiple retrieval results for better accuracy.

And much more!

---
## Agentic RAG  ⚙️  
Here are the details of all the Agentic RAG use cases covered in this repository.

## **AI Agents and Use Cases ⚙️**



| Title            | Description                                                                 | GitHub (link) |
|------------------|-----------------------------------------------------------------------------|----------------|
| **Financial AI Agent** | This Colab notebook showcases a multi-agent Conversational AI system for financial intelligence using the Google Gemini model, AGNO AI’s agent framework, DuckDuckGoTools, and YFinanceTools. It performs web research, stock analysis, macroeconomic trend tracking, and cryptocurrency insights using RAG-based retrieval. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agentic-Rag/Financial_AI_Agents_RAG_AGNO.ipynb) |
| **Email Voice Assistant**    | This Colab notebook builds a voice-controlled assistant using OpenAI GPT-4, Whisper, Gradio, and function calling to send emails and schedule meetings. It transcribes audio input, interprets commands, and triggers functions like send_email and schedule_meeting with natural voice interaction. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agentic-Rag/email_voice_assistant.ipynb) |
| **Follow-up Automation Agent**         | This Colab notebook presents an AI agent workflow that automates sales follow-up tasks using OpenAI GPT-4 with function calling. Given a sales call transcript, the agent intelligently extracts next steps, drafts relevant emails, and sends them—mimicking human-like follow-up execution in a modular, multi-step flow. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agentic-Rag/followup_automation_agent.ipynb) |

---

## **Agents ⚙️**  

Here are the details of all the **Agents** use cases covered in this repository.

| Title            | Description                                                                 | GitHub (link) |
|------------------|-----------------------------------------------------------------------------|----------------|
| **YouTube Summarizer** | This Colab notebook builds a YouTube summarization agent using agno.ai, OpenAI GPT-4, and YouTube transcript tools. It extracts video transcripts, identifies key segments with timestamps, and generates clear, structured summaries. Ideal for fast video analysis, content research, or review—streamlined with markdown formatting and agent-based orchestration. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agents/YouTube_Summarizer_Agno.ipynb) |
| **Trip Planner AI**  | This Colab notebook builds a text-based travel booking agent using OpenAI GPT-4 and function calling. It enables conversational booking of flights and hotels, integrates tool execution, and evaluates performance via Llumo Agentic API. Ideal for prototyping travel bots and demonstrating agentic workflows with real-time booking logic. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agents/Text_Based_Travel_Booking_Agent.ipynb) |
| **DevOps Assistant** | This Colab notebook showcases a DevOps Command Line Assistant powered by agno agents and OpenAI GPT-4. The assistant converts natural language into DevOps actions, routing tasks like restarting Linux services, managing Kubernetes clusters, running Terraform plans, or triggering CI/CD pipelines to the correct specialist agent. It also supports automatic evaluation of responses using Llumo AI analytics for metrics like Confidence.  | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agents/DevOps_Command_Assistant.ipynb) |
| **HelpDesk Assistant** | This Colab notebook builds an AI assistant for customer support using GPT-4 function calling. It handles ticket creation, tagging, escalation, closing, and history retrieval. Conversations are chunked for Llumo’s Agentic Eval API, enabling performance evaluation of tool-triggering behavior across user turns. The system runs fully automated without manual logic. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agents/Customer_Support_Conversation_Agent.ipynb) |
| **WebSummarizer AI** | This Colab notebook builds a web agent that extracts and summarizes full article content from any URL using Newspaper3k, OpenAI, and Agno. Ideal for media monitoring, research, or RAG pipelines, it outputs clean, human-readable summaries in markdown for easy analysis and downstream use. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agents/Autonomous_Web_Crawling_%26_Content_Summarization_Agent.ipynb) |

---

## **RAG ⚙️**  

Here are the details of all the **RAG** use cases covered in this repository.

| Title            | Description                                                                 | GitHub (link) |
|------------------|-----------------------------------------------------------------------------|----------------|
| **Ask My PDF** | This Colab notebook builds a RAG system that extracts text, tables, and images from PDFs using Unstructured, embeds them with OpenAIEmbeddings, and stores them in FAISS. LangChain retrieves relevant chunks to answer queries using ChatOpenAI. It also evaluates answers via Llumo Agentic Eval API for context utilization. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/RAG/Chat_with_pdf.ipynb) |
| **Sales Strategy Builder**  | This Colab notebook builds a strategy report agent using Google Gemini to analyze sales transcripts. It extracts client needs, solutions, objections, next steps, and strategic insights. The report is function-called, tool-wrapped, and evaluated via Llumo AI analytics for confidence and clarity—ideal for structured sales analysis and insight generation. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/RAG/Sales_Strategy_Builder.ipynb) |
| **MultiMind RAG** | This Colab notebook builds a multi-retriever RAG chatbot using GPT-4, Unstructured, FAISS, Wikipedia, and Tavily. It extracts content from PDFs, performs live web and Wikipedia search, and answers queries with LLUMO-powered evaluation—ideal for deep research and structured document QA. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/RAG/multi_source_helpdesk_faq_bot.ipynb) |
| **Table Data Q/A** | This Colab notebook uses PandasAI with OpenAI to analyze sales data through natural language queries. It loads a sample dataset, initializes OpenAI’s LLM, and creates a SmartDataFrame. Users can ask questions like revenue, top products, or customer rankings, and the model returns accurate insights with optional visualizations. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/RAG/table_data_qa.ipynb) |

---





## 🤖 Agentic RAG: Taking It a Step Further

Agentic RAG introduces **AI agents** that can interact with different tools, refine retrieved results, or even search the web dynamically. These techniques help make AI systems more flexible and adaptive.

Some key agentic techniques include:

- **Self-RAG** – Ensures responses are complete and accurate by double-checking retrieved data.
- **Corrective RAG** – Filters out irrelevant information and refines search queries.
- **Adaptive RAG** – Adjusts retrieval strategies based on the type of query.
- **ReAct RAG** – Combines reasoning and retrieval to improve contextual understanding.

With these techniques, AI systems don’t just passively retrieve information—they actively refine their responses.

---

## 🛠️ Getting Started

To get started, simply clone this repo:

```bash
git clone https://github.com/Llumo-AI/AI-Agents-RAG-Recipes.git
cd AI-Agents-RAG-Recipes
```
