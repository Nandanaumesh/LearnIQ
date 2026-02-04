# LearnIQ – AI-Powered Learning from Code Failures

LearnIQ is an AI-powered educational platform that transforms failed code submissions into personalized learning experiences.  
Instead of debugging or fixing code, LearnIQ identifies **conceptual misunderstandings** and generates **targeted micro-lessons** to help learners truly understand where they went wrong.

This project is built for the **AI for Bharat Hackathon** under the **AI for Learning & Developer Productivity** track.

---

## 🚀 Problem Statement

When learners submit incorrect code:
- Platforms only show test case failures or error messages
- Learners struggle to understand *which concept* they misunderstood
- Repeated trial-and-error slows learning and productivity

There is a gap between **code failure** and **conceptual understanding**.

---

## 💡 Solution: LearnIQ

LearnIQ uses AI to:
1. Analyze failed code submissions
2. Identify underlying **conceptual gaps**
3. Generate **personalized micro-lessons**
4. Update a learner’s **adaptive learning path**

The focus is **learning from failure**, not automated debugging.

---

## 🧠 Key Features

- 🔍 Conceptual gap identification (not syntax-only errors)
- 🎯 Personalized micro-lessons based on mistakes
- 🧭 Adaptive learning paths with progress tracking
- 🤖 AI-powered reasoning using Amazon Bedrock
- ☁️ Scalable, serverless AWS architecture
- 🏫 Designed for universities, skilling programs, and government initiatives

---

## 🏗️ System Architecture

The system follows a **serverless, event-driven AWS architecture**.

**High-level flow:**
1. Learner submits failed code via Web or LMS
2. API Gateway routes the request to AWS Lambda
3. Code stored in Amazon S3, metadata in DynamoDB
4. AI Analysis Lambda sends code to Amazon Bedrock
5. Conceptual gaps are identified
6. Content Generation Lambda creates micro-lessons
7. Lessons stored in S3 and learning path updated
8. Learner receives personalized learning content

> 📌 The architecture diagram in `design.md` was generated using **AWS MCP** and rendered using **Mermaid syntax**.

---

## 🧰 Technology Stack

- **Backend:** AWS Lambda, API Gateway
- **AI Services:** Amazon Bedrock (LLM-based reasoning & content generation)
- **Storage:** Amazon S3, Amazon DynamoDB
- **Architecture Style:** Serverless, microservices
- **Diagram Generation:** AWS MCP + Mermaid
- **Language (Planned):** Python

---

## 🧑‍🎓 Target Users

- Students learning programming
- Educators and instructors
- Universities and coding platforms
- Government skilling and digital education programs

---

## 📄 Project Documents

- `requirements.mmd` – Functional and non-functional requirements
- `design.md` – System design, architecture, data models, and correctness properties
- `README.md` – Project overview (this file)

---

## 🏆 Hackathon Alignment

- **Track:** AI for Learning & Developer Productivity
- **Focus:** Faster learning, conceptual clarity, meaningful AI usage
- **Novelty:** Treats failed code as a learning signal, not an error to fix
- **Scalability:** Designed for large-scale educational deployment in India

---

## 📌 Status

- ✅ Idea submission completed
- ✅ Architecture designed
- ✅ AWS MCP diagram generated
- 🚧 Prototype development planned for Phase 2 (if shortlisted)

---

## 🤝 Team

Built as part of the **AI for Bharat Hackathon**.

