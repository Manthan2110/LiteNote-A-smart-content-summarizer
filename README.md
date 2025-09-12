```txt
██╗       ██╗  ████████╗  ███████╗███╗   ██╗ ██████╗ ████████╗███████╗
██║       ██║  ╚══██╔══╝  ██╔════╝████╗  ██║██╔═══██╗╚══██╔══╝██╔════╝
██║       ██║     ██║     █████╗  ██╔██╗ ██║██║   ██║   ██║   ███████╗
██║       ██║     ██║     ██╔══╝  ██║╚██╗██║██║   ██║   ██║   ╚════██║
███████╗  ██║     ██║     ███████╗██║ ╚████║╚██████╔╝   ██║   ███████║
╚══════╝  ╚═╝     ╚═╝     ╚══════╝╚═╝  ╚═══╝ ╚═════╝    ╚═╝   ╚══════╝
```


# 📘 LiteNote
### Smart Summaries, Simplified.

## 🚀 Elevator Pitch
Tired of sitting through long YouTube videos, endless articles, or bulky documents? LiteNote is your AI-powered companion that condenses hours of content into clear, actionable notes. Save time, capture insights, and focus only on what matters — your quick path from lengthy content to bite-sized knowledge.

---

## ✨ Features
- 🎥 YouTube Video Summaries – Extract transcripts and get the key takeaways in seconds.
- 📄 Document Summaries – Turn long PDFs, articles, and text files into concise notes.
- ⚡ AI-Powered Gist – Understand context, not just text. LiteNote delivers clarity.
- 🖥️ Minimal UI – Lightweight and intuitive interface, built for speed and focus.
- 🔄 Multiple Formats – Copy, save, or share your summaries instantly.

---

## 🛠️ How It Works
1. Paste a YouTube link or upload your document/text.
2. LiteNote extracts the transcript or text content.
3. The AI generates a crisp, structured summary highlighting the key points.
4. Done! You get clear, digestible notes in seconds.

---

## 🛠️ Tech Stack  

- [Streamlit](https://streamlit.io/) – Frontend framework  
- [Google Gemini AI](https://ai.google/) – Generative AI for summarization  
- [YouTube Transcript API](https://github.com/jdepoix/youtube-transcript-api) – Transcript extraction  
- [Trafilatura](https://trafilatura.readthedocs.io/) – Web content extraction  
- [Newspaper3k](https://newspaper.readthedocs.io/) – Article parsing  
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) – HTML parsing fallback  
- [FPDF](https://pyfpdf.github.io/fpdf2/) – PDF export  
- [python-docx](https://python-docx.readthedocs.io/) – Word export  
- [python-pptx](https://python-pptx.readthedocs.io/) – PowerPoint export  

---

## 🚀 Quick Start

### Prerequisites
- Python **3.8+**
- Google Gemini API key ([Get it here](https://makersuite.google.com/app/apikey))

### Installation

```bash
# Clone project
git clone https://github.com/Manthan2110/LiteNote.git

# Move into project folder
cd LiteNote

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

---

## 🖼️ Example Output
Input: YouTube video (20 minutes) on AI in Healthcare.
Output (LiteNote):
  - AI improves early disease detection.
  - Reduces diagnostic errors by 40%.
  - Enables personalized treatment plans.
  - Ethical challenges still need addressing.

From 20 minutes → 4 bullet points. 💡

-- 
## 💡 Why LiteNote?
- ⏳ Save Time: No more wasting hours watching or reading.
- 🧠 Stay Informed: Get the core insights fast.
- 🎯 Be Productive: Focus on action, not consumption.
  
---

## ⚠️ Known Issues
- YouTube Transcript Extraction may fail if:
    - YouTube blocks requests due to too many rapid queries from your IP.
    - You’re running from cloud-hosted environments (e.g., AWS/GCP).
      👉 Workaround: Run locally or use proxies as suggested in [YouTube Transcript API README](https://github.com/jdepoix/youtube-transcript-api#working-around-ip-bans-requestblocked-or-ipblocked-exception)

---

## 🤝 Contributing
Contributions are welcome! Feel free to:
- Open an issue 🐞
- Suggest new features 💡
- Submit a pull request 🔥

---

## 📜 License
MIT License – free to use, modify, and share.

---

## 🔥 With LiteNote, you don’t just read or watch — you understand faster.
