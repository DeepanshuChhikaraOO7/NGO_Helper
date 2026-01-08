# 🤖 NGO Helper: The Agentic Proposal Architect

**NGO Helper** is an advanced Multi-Agent AI system designed to empower non-profits (NGOs) by automating the creation of high-impact, professional project proposals. Built with a focus on the Indian socio-legal landscape, it bridges the gap between vision and execution.

## 🚀 The Vision

Writing a grant-winning proposal requires deep research, financial planning, and legal compliance. **NGO Helper** uses a collaborative group of specialized AI agents to handle these complexities, allowing NGO workers to focus on their mission—not paperwork.

## 🧠 System Architecture: Multi-Agent Collaboration

Instead of a single prompt, this system uses a **Research Group** of specialized agents built with **LangChain**:

* **The Registrar Agent:** Handles initial documentation and alignment with the organization's mission.
* **The Impact Architect:** Drafts the problem statement and defines the "Theory of Change."
* **The Operations Lead:** Develops the 12-month project timeline and key milestones.
* **The Budget Officer:** Ensures mathematical accuracy in financial requests (INR).
* **The Partnership Agent:** Identifies potential synergy with CSR partners and government schemes.

## 🛠️ Tech Stack

| Component | Technology |
| --- | --- |
| **Orchestration** | LangChain (Chains & Tools) |
| **LLMs** | Groq (Llama-3) & Google Gemini 2.5 Flash Lite |
| **Web Research** | Tavily Search API & Wikipedia Tool |
| **Database/Storage** | Supabase |
| **Frontend** | Streamlit |
| **Data Validation** | Pydantic (Structured Output) |

## 📦 Features

* **Context-Aware Research:** Uses Tavily to pull real-time data about specific regions (e.g., Haryana, India).
* **Structured Output:** Generates clean HTML/Markdown proposals ready for export.
* **Legal Integration:** Includes references to relevant laws (e.g., BNS, IPC) for legal compliance.
* **Modular Codebase:** Separated `agents.py` for easy debugging and scalability.

## 🛠️ Installation & Setup

1. **Clone the repository:**
```bash
git clone https://github.com/DeepanshuChhikaraOO7/NGO_Helper.git
cd NGO_Helper

```


2. **Install dependencies:**
```bash
pip install -r requirements.txt

```


3. **Environment Variables:**
Create a `.env` file and add your keys:
```env
GROQ_API_KEY=your_key
GOOGLE_API_KEY=your_key
TAVILY_API_KEY=your_key
SUPABASE_URL=your_url
SUPABASE_KEY=your_key

```


4. **Run the App:**
```bash
streamlit run main_app.py

```



## 📝 Example Test Case

To test the "Agentic" reasoning, try the following input:

* **Project:** "Wheels of Wisdom" (Mobile Digital Literacy)
* **Location:** Jhajjar, Haryana
* **Budget:** ₹12,50,000
* **Goal:** Provide computer training to 500+ rural students.

---

**Developed by [Deepanshu Chhikara](https://www.linkedin.com/in/deepanshu-chhikara007/)**
*Aspiring Agentic AI Engineer & Data Analyst*
