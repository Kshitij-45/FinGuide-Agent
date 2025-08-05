🧠 FinGuide Agent -- AI for Digital Financial Literacy

FinGuide Agent is a multilingual AI assistant built using IBM Watsonx.ai
and Granite foundation models. It helps users understand essential
aspects of digital finance such as UPI, interest rates, bank accounts,
budgeting, and scam prevention. The assistant uses Retrieval-Augmented
Generation (RAG) to ground answers in reliable government and banking
documents, and supports interaction in regional languages through IBM
Language Translator.

🔍 Problem Statement

AI Agent for Digital Financial LiteracyAn AI assistant that retrieves
and explains trusted content from RBI, NPCI, SEBI, and other reliable
financial sources to help users understand UPI, online scams, interest
rates, budgeting, and personal finance. It supports multilingual
interaction and uses RAG + IBM Granite LLMs to ensure grounded,
personalized, and accessible knowledge.

🔹 Proposed Solution

FinGuide Agent is a multilingual AI assistant hosted on IBM Cloud Lite,
powered by Watsonx.ai's Granite model and RAG. It retrieves relevant
information from government documents (like RBI FAQs and UPI
guidelines), vectorizes the content, and generates context-aware
answers. IBM Language Translator supports multilingual input/output,
making the tool inclusive, accessible, and fraud-aware.

🚀 Key Features

💬 Natural Language Q&A using RBI and NPCI official documents

🧠 Granite LLM for intelligent, personalized response generation

📊 RAG-based Architecture for grounded, document-backed answers

🌍 Multilingual Support through IBM Language Translator

☁️ IBM Cloud Lite Hosting without any external dependencies

🔍 Sample Questions for Testing

"How do I send money using UPI?"

"What is a UPI PIN and how to reset it?"

"Can I open a Basic Savings Bank Deposit Account without full KYC
documents?"

"What should I do if I accidentally send money to the wrong UPI ID?"

🤝 Who Are the End Users?

👵 General Public -- Especially those new to digital banking and UPI

📱 First-time UPI/Smartphone Users in rural and semi-urban areas

👩‍🎓 Students and Young Adults exploring personal finance

📋 Low-Income or Unbanked Individuals seeking guidance on secure banking

🔋 Target End Users

Same as above:

General public unfamiliar with digital banking

First-time UPI users from rural/semi-urban backgrounds

Young learners and students trying to become financially aware

Low-income citizens aiming to safely access banking and digital payments

🌟 Wow Factors

🔍 Context-aware RAG ensures grounded, reliable answers from official
documents

🌎 Multilingual capabilities make it accessible across languages and
regions

🚫 Scam prevention focused to promote safe digital practices

☁️ 100% IBM Cloud Lite solution with no external costs or services

🚪 Tech Stack Overview

Component

Technology

Language Model

IBM Watsonx.ai -- Granite 13B

RAG Pipeline

Watsonx Prompt Lab / Python

Vector Store

In-Memory / Milvus / Watsonx.data

Multilingual Translation

IBM Language Translator API

File Storage

IBM Cloud Object Storage

Interface

Watsonx Prompt Lab (no-code UI)

🔹 Conclusion

🤝 FinGuide Agent simplifies financial literacy for every user segment.

🌐 Makes multilingual digital banking education accessible and secure.

🧠 Leverages IBM Granite and RAG for trustworthy, contextual answers.

☁️ Fully deployable using IBM Cloud Lite for free and scalable
deployment.

🔮 Future Scope

🌎 Expand language support for broader inclusivity across India

📱 Integrate with mobile banking apps or chatbot platforms

📈 Include more financial topics like insurance, tax, and mutual funds

🎤 Add voice assistant support for non-literate or visually impaired
users

📚 License

This project is for educational and demonstration purposes. Always
consult official sources or financial advisors before making banking
decisions.

🌟 Contributors

Kshitij Zure -- Project lead, developer, prompt engineer

IBM Cloud & Watsonx Studio -- AI platform support
