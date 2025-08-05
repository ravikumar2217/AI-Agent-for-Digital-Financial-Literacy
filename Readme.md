# 🧠AI Agent for Digital Financial Literacy

This AI Agent is a multilingual AI assistant built using IBM Watsonx.ai
and Granite foundation models. It helps users understand key aspects of
digital finance like UPI usage, banking rules, interest rates,
budgeting, and scam protection --- all grounded using
Retrieval-Augmented Generation (RAG) from trusted documents like RBI
FAQs and NPCI guidelines.

------------------------------------------------------------------------

## 🔍 Problem Statement

> **AI Agent for Digital Financial Literacy**\
> An AI agent that retrieves information from reliable financial sources
> (RBI, NPCI, SEBI) and answers user queries about digital banking tools
> such as UPI, budgeting, interest rates, and fraud prevention. It
> supports multiple languages and uses IBM Granite LLM with RAG to
> provide grounded, personalized, and accessible financial knowledge.

------------------------------------------------------------------------

## ✅ Key Features

-   💬 **Question Answering** based on official PDFs from RBI, NPCI\
-   🧠 **Powered by IBM Granite LLMs** using Watsonx.ai\
-   📚 **RAG (Retrieval-Augmented Generation)** for grounded,
    context-rich responses\
-   🌐 **Multilingual Support** using IBM Language Translator (e.g.,
    Hindi, Marathi)\
-   ☁️ **Fully hosted on IBM Cloud Lite**, no external tools required

------------------------------------------------------------------------

## 👥 Target End Users

-   General public unfamiliar with digital banking\
-   First-time UPI/smartphone users in rural areas\
-   Students and young adults learning personal finance\
-   Low-income or unbanked individuals needing banking guidance

------------------------------------------------------------------------

## 🚀 How It Works

1.  🔹 Upload RBI and UPI guideline documents (PDF, TXT) to Watsonx
    project\
2.  🔹 Vectorize documents using Watsonx Prompt Lab or Notebooks\
3.  🔹 Accept user question → retrieve relevant text chunks (RAG)\
4.  🔹 Pass context + question to Granite model → generate response

------------------------------------------------------------------------

## 🧪 Sample Questions

-   *"How do I send money using UPI?"*\
-   *"What is a UPI PIN and how to reset it?"*\
-   *"Can I open a bank account without full KYC?"*\
-   *"What should I do if I send money to the wrong UPI ID?"*

------------------------------------------------------------------------

## 🧰 Tech Stack

  Component                  Technology
  -------------------------- -----------------------------------
  Language Model             IBM Watsonx.ai -- Granite 13B
  RAG Pipeline               Watsonx Prompt Lab / Python
  Vector Store               In-Memory / Milvus / Watsonx.data
  Multilingual Translation   IBM Language Translator API
  File Storage               IBM Cloud Object Storage
  Interface                  Watsonx Prompt Lab (no-code UI)

------------------------------------------------------------------------

## 🌟 Wow Factors

-   RAG-enabled answers from trusted RBI/NPCI documents\
-   IBM Granite LLM ensures scalable and reliable generation\
-   Multilingual input/output for inclusive user experience\
-   Fully cloud-hosted using IBM Cloud Lite (free tier)

  -----------------
  \## ✅ Conclusion
  🔐 FinGuide Agent
  empowers users
  with accurate,
  safe, and
  grounded
  financial
  knowledge.

  🌐 It supports
  diverse language
  users, bridging
  the gap in
  digital financial
  literacy.

  🧠 Powered by IBM
  Watsonx.ai and
  Granite models,
  it ensures
  context-aware,
  reliable answers.

  ☁️ Fully
  deployable using
  IBM Cloud Lite
  services, making
  it scalable,
  cost-effective,
  and accessible.
  -----------------

### 🔮 Future Scope

-   🌍 *Wider Language Support* -- Add more Indian and global languages
    for deeper inclusivity.
-   📱 *Mobile App Integration* -- Deploy the agent in WhatsApp or
    mobile banking apps for easier access.
-   🧾 *Expanded Knowledge Base* -- Include more financial topics like
    insurance, mutual funds, and taxation.
-   🤖 *Voice Assistant Integration* -- Enable voice-based interactions
    for non-literate or visually impaired users.

------------------------------------------------------------------------

##🌟 Contributors

Ravi Kumar -- Project lead, developer

IBM Cloud & Watsonx Studio -- AI platform support
