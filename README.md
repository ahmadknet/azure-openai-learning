# 30-Day Azure OpenAI Learning Plan

## For a Senior .NET Developer (15+ Years)

### Goal

Build a GitHub repository:

```text
azure-openai-learning
```

By Day 30, you should be able to:

* Explain Azure OpenAI architecture
* Build AI-powered .NET applications
* Understand Prompt Engineering
* Build RAG applications
* Understand AI Agents
* Integrate Azure OpenAI into ASP.NET Core APIs

---

# Repository Structure

```text
azure-openai-learning
│
├── Week01-Fundamentals
├── Week02-PromptEngineering
├── Week03-RAG
├── Week04-AIApplications
│
└── README.md
```

---

# Week 1

# Azure OpenAI Fundamentals

## Day 1

### What is Azure OpenAI?

Create:

```text
01-WhatIsAzureOpenAI.md
```

Learn:

* OpenAI vs Azure OpenAI
* Enterprise AI
* Security
* Compliance

Understand:

```text
User
↓
Application
↓
Azure OpenAI
↓
Response
```

---

## Day 2

### LLM Fundamentals

Create:

```text
02-LLM.md
```

Learn:

* What is an LLM?
* GPT Models
* Tokens
* Context Window

Examples:

* ChatGPT
* GPT-4
* GPT-5

---

## Day 3

### Tokens

Create:

```text
03-Tokens.md
```

Learn:

* Input Tokens
* Output Tokens
* Cost Calculation

Example:

```text
1000 Tokens ≈ 750 Words
```

---

## Day 4

### Temperature

Create:

```text
04-Temperature.md
```

Learn:

```text
0.0 = Deterministic

1.0 = Creative
```

---

## Day 5

### Prompts

Create:

```text
05-Prompts.md
```

Examples:

```text
Generate 20 C# Interview Questions.
```

```text
Explain Dependency Injection.
```

---

## Day 6

### System Prompts

Create:

```text
06-SystemPrompts.md
```

Example:

```text
You are a Senior .NET Architect.
```

---

## Day 7

### Build Notes Summary

Create:

```text
Week01-Summary.md
```

---

# Week 2

# Prompt Engineering

---

## Day 8

### Zero-Shot Prompting

Create:

```text
07-ZeroShot.md
```

---

## Day 9

### Few-Shot Prompting

Create:

```text
08-FewShot.md
```

---

## Day 10

### Chain of Thought

Create:

```text
09-ChainOfThought.md
```

---

## Day 11

### Role-Based Prompting

Examples:

```text
Act as a Senior .NET Architect
```

---

## Day 12

### Structured Outputs

Learn:

* JSON Output
* Tables
* Markdown

---

## Day 13

### Prompt Templates

Create:

```text
10-PromptTemplates.md
```

Examples:

* Resume Review
* Code Review
* Interview Questions

---

## Day 14

### Build Mini Project

Repository Folder:

```text
MiniProjects/InterviewGenerator
```

Project:

Generate .NET Interview Questions

---

# Week 3

# RAG (Most Important)

---

## Day 15

### What is RAG?

Create:

```text
11-RAG.md
```

Architecture:

```text
Documents
↓
Chunking
↓
Embeddings
↓
Vector Search
↓
LLM
```

---

## Day 16

### Chunking

Create:

```text
12-Chunking.md
```

---

## Day 17

### Embeddings

Create:

```text
13-Embeddings.md
```

Learn:

* Similarity Search
* Vector Search

---

## Day 18

### Vector Databases

Create:

```text
14-VectorDatabases.md
```

Examples:

* Azure AI Search
* ChromaDB

---

## Day 19

### Azure AI Search

Create:

```text
15-AzureAISearch.md
```

---

## Day 20

### RAG Architecture

Create:

```text
16-RAGArchitecture.md
```

Architecture:

```text
React
↓
ASP.NET Core
↓
Azure AI Search
↓
Azure OpenAI
```

---

## Day 21

### Build RAG Notes Summary

Create:

```text
Week03-Summary.md
```

---

# Week 4

# Real AI Applications

---

## Day 22

### AI Chatbot

Create:

```text
17-AIChatbot.md
```

Architecture:

```text
React
↓
ASP.NET Core
↓
Azure OpenAI
```

---

## Day 23

### Resume Reviewer

Create:

```text
18-ResumeReviewer.md
```

---

## Day 24

### Document Summarizer

Create:

```text
19-DocumentSummarizer.md
```

---

## Day 25

### Meeting Notes Generator

Create:

```text
20-MeetingNotesGenerator.md
```

---

## Day 26

### AI Agents

Create:

```text
21-AIAgents.md
```

Learn:

```text
LLM
+
Tools
+
Memory
+
Planning
```

---

## Day 27

### Semantic Kernel

Create:

```text
22-SemanticKernel.md
```

Focus on:

* Kernel
* Plugins
* Function Calling

---

## Day 28

### AI Architecture

Create:

```text
23-AIArchitecture.md
```

Enterprise Architecture:

```text
React
↓
ASP.NET Core
↓
Semantic Kernel
↓
Azure OpenAI
```

---

## Day 29

### AI-Powered Enterprise Applications

Create:

```text
24-AIEnterpriseApps.md
```

Examples:

* HRMS
* CRM
* Knowledge Assistant

---

## Day 30

### Master Revision

Create:

```text
AzureOpenAICheatSheet.md
```

Include:

* LLM
* Tokens
* Prompts
* Temperature
* RAG
* Embeddings
* Azure AI Search
* Semantic Kernel
* AI Agents

---

# Final GitHub Structure

```text
azure-openai-learning
│
├── 01-WhatIsAzureOpenAI.md
├── 02-LLM.md
├── 03-Tokens.md
├── 04-Temperature.md
├── 05-Prompts.md
├── 06-SystemPrompts.md
├── 07-ZeroShot.md
├── 08-FewShot.md
├── 09-ChainOfThought.md
├── 10-PromptTemplates.md
├── 11-RAG.md
├── 12-Chunking.md
├── 13-Embeddings.md
├── 14-VectorDatabases.md
├── 15-AzureAISearch.md
├── 16-RAGArchitecture.md
├── 17-AIChatbot.md
├── 18-ResumeReviewer.md
├── 19-DocumentSummarizer.md
├── 20-MeetingNotesGenerator.md
├── 21-AIAgents.md
├── 22-SemanticKernel.md
├── 23-AIArchitecture.md
├── 24-AIEnterpriseApps.md
│
├── AzureOpenAICheatSheet.md
└── README.md
```

# Outcome After 30 Days

You'll be able to discuss confidently in interviews:

* Azure OpenAI
* GPT Models
* Prompt Engineering
* RAG
* Embeddings
* Azure AI Search
* Semantic Kernel
* AI Agents
* Enterprise AI Architecture

And more importantly, you'll be able to connect these concepts directly to your existing expertise in **ASP.NET Core, Microservices, Azure, and Enterprise Application Development**, which is exactly how senior .NET engineers are being hired into AI-related roles.
