# phidata-AI-Agents

A powerful, LLaMA 3-based intelligent assistant built with the Phi framework and Groq’s blazing-fast inference engine. This project uses a single-agent and multi-agent setup to fetch real-time web content and financial data, including analyst recommendations and stock fundamentals — all displayed in clean, Markdown-formatted tables.

---

## 🚀 Features

* 🧠 **Groq + LLaMA 3.3 70B**: Leverages Groq’s high-performance transformer engine.
* 🔎 **Web Agent**: Fetches real-time news using DuckDuckGo (multi-agent setup).
* 📊 **Finance Agent**: Retrieves stock prices, analyst insights, and company data via Yahoo Finance.
* 🤝 **Team Coordination**: Combines multiple specialized agents for complex queries.
* 🧾 **Markdown Responses**: Outputs structured data and tables in markdown.
* 🐞 **Debug Mode**: View tool invocations and agent logic for transparency.

---

## 🛠️ Installation

1. **Clone the Repository**

```bash
git clone https://github.com/gautamshah01/phidata-AI-Agents.git
cd phidata-AI-Agents
```

2. **Set up a virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Configure `.env`**

Create a `.env` file in the root directory:

```env
# .env
GROQ_API_KEY=your_groq_api_key_here
```


---


### 🧩 Add More Tools or Instructions

You can extend the `Agent` with more tools or custom functions. Just include them in the `tools` list and update the `instructions`.

---

## 🤝 Contributing

Pull requests and ideas are welcome — feel free to open an issue to start a discussion.
