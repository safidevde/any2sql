# Any2SQL

**Any2SQL** is an AI-powered tool that converts plain English descriptions of data needs into SQL queries you can run against your database. It prioritizes **security** and **clarity**, letting you generate clean SQL without exposing your underlying data.

<!-- image fromn gihhub repo -->
[![Any2SQL Logo](https://raw.githubusercontent.com/safidevde/any2sql/main/screenshot.png)](https://any2sql.com/)

## 🚀 Features

### 🗣️ Natural Language → SQL
Describe what you want in everyday language and the AI generates corresponding SQL — ideal for users who don’t want to hand-write complex queries.

### 🔒 Schema-Only AI Access
The AI only sees your **table structure** (names and columns), never your actual sensitive data. This design protects your data while still enabling accurate SQL generation.

### 📊 Built-In Visualization
Quickly visualize query results with simple **bar and line charts** directly within the interface.

### 🧠 Advanced Models Support
Use cutting-edge language models like **OpenAI GPT-5 mini** or **Google Gemini** for high-quality SQL generation.

### 📦 Pro Plan Capabilities
With a paid plan (~$7/month), you get:
- **1200 queries/month**
- Support for multiple data sources (PostgreSQL & MySQL)
- Mock datasource generation
- API endpoints to run queries programmatically
- Workspaces (multi-user support)
- Query fixing and execution
- Visualizations
- Email support


## 🔐 Security & Safety

- Database credentials are encrypted (**AES-256** at rest) and TLS/SSL-protected in transit.
- The system is designed to generate and execute **SELECT** queries by default; it’s recommended to use a **read-only database user** to avoid unintentional data changes.

## 🛠️ Supported Databases

At present, Any2SQL supports:
- **PostgreSQL**
- **MySQL**
More data sources are planned in future releases.

## 📦 API Integration

Any2SQL provides secure API endpoints you can call to:
- Run generated SQL
- Return results in **JSON**
- Integrate with automation or workflow tools like **n8n**, **Zapier**, or custom applications
Each request is authenticated with your API key and supports pagination.

## ⚡ Getting Started

1. Visit https://any2sql.com/
2. Sign up for a free trial (3 days free).
3. Connect your database (PostgreSQL or MySQL).
4. Type natural text describing the data you want or the sql you want to fix.
5. Generate and copy the SQL — or run it and visualize results.

## 📄 FAQs

**Is my actual data ever read by the AI?**
No — only the schema structure is visible to the AI.

**Can the AI modify my data?**
By default, it won’t generate data-modifying commands, especially if you use a read-only account.

**Does it support GPT-5 or Gemini models?**
Yes — flagship AI models are available in the Pro plan.

---

