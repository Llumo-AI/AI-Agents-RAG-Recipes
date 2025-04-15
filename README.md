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

| Title            | Description                                                                 | GitHub (link) |
|------------------|-----------------------------------------------------------------------------|----------------|
| Finacial Ai Agent | Uses AI agents with vectordb and web search to retrieve and generate answers. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agentic-Rag/Financial_AI_Agents_RAG_AGNO.ipynb) |
| Email Voice Assistant    | Refines relevant documents, removes irrelevant ones or performs web search. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agentic-Rag/email_voice_assistant.ipynb) |
| Followup Automation Agent         | Reflects on retrieved data to ensure accurate and complete responses.       | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agentic-Rag/followup_automation_agent.ipynb) |

## Agents  ⚙️  
Here are the details of all the Agents use cases covered in this repository.

| Title            | Description                                                                 | GitHub (link) |
|------------------|-----------------------------------------------------------------------------|----------------|
| YouTube Summarizer | Uses AI agents with vectordb and web search to retrieve and generate answers. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agents/YouTube_Summarizer_Agno.ipynb) |
| Trip Planner AI  | Refines relevant documents, removes irrelevant ones or performs web search. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agents/Text_Based_Travel_Booking_Agent.ipynb) |
| DevOps Assistant | Reflects on retrieved data to ensure accurate and complete responses.       | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agents/DevOps_Command_Assistant.ipynb) |
| HelpDesk Assistant | Refines relevant documents, removes irrelevant ones or performs web search. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agents/Customer_Support_Conversation_Agent.ipynb) |
| WebSummarizer AI | Reflects on retrieved data to ensure accurate and complete responses.       | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/Agents/Autonomous_Web_Crawling_%26_Content_Summarization_Agent.ipynb) |


## Rag  ⚙️  
Here are the details of all the Rag use cases covered in this repository.

| Title            | Description                                                                 | GitHub (link) |
|------------------|-----------------------------------------------------------------------------|----------------|
| Ask My PDF | Uses AI agents with vectordb and web search to retrieve and generate answers. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/RAG/Chat_with_pdf.ipynb) |
| Sales Strategy Builder  | Refines relevant documents, removes irrelevant ones or performs web search. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/RAG/Sales_Strategy_Builder.ipynb) |
| MultiMind RAG | Reflects on retrieved data to ensure accurate and complete responses.       | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/RAG/multi_source_helpdesk_faq_bot.ipynb) |
| Table Data Q/A | Refines relevant documents, removes irrelevant ones or performs web search. | [🔗 GitHub](https://github.com/Llumo-AI/AI-Agents-RAG-Recipes/blob/main/RAG/table_data_qa.ipynb) |






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
