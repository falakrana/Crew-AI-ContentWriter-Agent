# 🧠 CrewAI Research & Blogger Agent

This project utilizes [CrewAI](https://github.com/joaomdmoura/crewai) to build a research and writing agent duo. It automates content generation for trending topics using **Google Gemini** and **Serper.dev** search tools. Ideal for bloggers, news content creators, and SEO writers.

---

## ✨ Features

- 🔎 **AI-Powered Researcher**: Extracts key insights, pros/cons, and narratives from current news or tech trends.
- ✍️ **AI Writer**: Transforms research into engaging, simplified blog articles in markdown.
- 🌐 **Web-augmented** using Serper.dev search API.
- 💬 Built on Google Gemini (via `langchain_google_genai`).

---

## 📁 Project Structure

```
├── agents.py # Defines Researcher & Writer agents with Gemini LLM
├── crew.py # Launches the workflow: Crew -> Tasks -> Output
├── tasks.py # Describes individual research & writing tasks
├── tools.py # Includes the Serper search tool
├── requirements.txt # Python dependencies
├── new-blog-post.md # Output sample (markdown-formatted blog)
└── README.md # You're here!
```


---

## 🚀 Getting Started

### 1. Clone the Repository

```
git clone https://github.com/yourusername/Crew-AI-ContentWriter-Agent.git
cd crewai-research-blogger
```


### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Configure Environment Variables
In .env

>> GOOGLE_API_KEY=your_google_gemini_api_key
>> SERPER_API_KEY=your_serper_api_key


### 4. Run the file:
```
crew.py
```

