# n8n Automation Engineer | AI Workflows & Agentic Systems

Hi, I'm Alaa — I build production-ready automation workflows using **n8n**, combining traditional automation logic with **AI Agents** that can reason, use tools, and handle real-world edge cases.

This repository is a collection of workflows I've designed and built, each one following a strict internal standard I apply to every project:

- **Error Handling** — workflows don't just stop when something fails. They retry, fall back gracefully, and record failures clearly.

- **Multiple Scenarios** — workflows validate inputs and route different cases separately instead of treating every input the same way.

- **Clean Output Formats** — results are returned in structured, readable formats such as JSON, tables, logs, or human-reviewable drafts.

I don't just connect nodes — I design workflows that are reliable enough to be used by a real business.

## Projects

| Project | Description | Key Concepts |
| --- | --- | --- |
| [AI-Assisted B2B Lead Research](./b2b-lead-research) | Researches B2B leads from Google Sheets, analyzes public company metadata, and creates Gmail drafts for human review without sending emails automatically | Batch Processing, HTTP Request, API Integration, AI Scoring, Gmail Drafts, Status Tracking |
| [AI Customer Support RAG](./ai-customer-support-rag) | A retrieval-augmented customer support agent that answers questions from a verified knowledge base and escalates unsupported requests to a human | RAG, Qdrant, Embeddings, Document Ingestion, AI Agent, Human Handoff |
| [AI Content Repurposing](./ai-content-repurposing) | Turns one source topic into four channel-ready Arabic content drafts for LinkedIn, Instagram, X/Twitter, and newsletters, with an AI quality gate | Multi-Channel Generation, Looping, Structured Output, Quality Gate, Human Review |
| [Customer Support Triage](./customer-support-triage) | Classifies incoming customer messages, drafts Egyptian Arabic replies, logs support tickets, and escalates urgent cases to a human agent | AI Classification, Confidence Gating, Memory, Routing, Ticket Logging |
| [Customer Feedback Escalation System](./customer-feedback-escalation-system) | Analyzes customer feedback for sentiment, urgency, topics, and follow-up needs, then routes routine and urgent cases separately | Sentiment Analysis, Priority Routing, Prompt Guardrails, Safe Replies, Escalation |
| [Sales Data Analyst](./sales-data-analyst) | An AI data-analysis workflow that validates sales questions, uses calculation tools, and returns structured answers from sales data | Data Analysis, AI Agent, Tool Use, Validation, Calculations, Structured Output |
| [News Automation](./news-automation) | Fetches daily news, filters relevant AI and technology stories, summarizes important articles in Egyptian Arabic, and delivers them to Telegram | Scheduled Workflows, External APIs, AI Filtering, Summarization, Rate Limiting |
| [Tavily Search Agent](./tavily-search-agent) | A Telegram bot powered by an AI Agent that searches the web in real time to answer user questions | AI Agent, Tool Use, Web Search, Input Validation, Error Handling, Memory |

*(More projects are being added regularly — this portfolio is actively growing.)*

## Tech I Work With

`n8n` `AI Agents` `OpenAI API` `Google Gemini` `Qdrant` `Tavily API` `Microlink API` `Gmail API` `Telegram Bot API` `Google Sheets` `Webhooks` `JSON` `REST APIs` `Prompt Engineering`

## Let's Work Together

I'm currently taking on freelance automation projects — from task automation to AI-powered agents that handle customer support, lead research, document search, content operations, and internal reporting.

If you have a repetitive process in your business that could be automated, or you need an AI agent that works reliably with validation, structured outputs, and human review, feel free to reach out.

**Contact:** Email: [alaaoka2002@gmail.com](mailto:alaaoka2002@gmail.com)
