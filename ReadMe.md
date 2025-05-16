
# YouTube Video to PPT Converter Using Python 🎥➡️📊

## 🚀 Project Overview

**YouTube Video to PPT Converter** is a Python-based tool that automates the process of converting YouTube videos into PowerPoint presentations. It extracts the video's transcript or audio, summarizes the content, and generates presentation slides with key points, optionally including visual frames from the video. This tool is designed to help educators, content creators, and students quickly transform video content into structured, offline-readable presentation material.

---

## 🧰 Features

* 🔗 Fetches videos directly from YouTube via URL
* 📝 Converts speech to text using transcript or speech recognition
* 🧠 Summarizes long content using NLP techniques
* 🖼️ Captures key video frames as slide visuals (optional)
* 📊 Automatically generates `.pptx` presentation files
* 💬 Supports multi-language transcription (if available)
* 🧪 Modular and customizable for different use-cases

---

## 📦 Tech Stack

* **Language**: Python 3.8+
* **Libraries**:

  * `pytube` – Download video and captions
  * `moviepy` – Extract frames and audio
  * `speech_recognition` – Convert speech to text (fallback)
  * `transformers` / `sumy` – Text summarization
  * `python-pptx` – Generate PowerPoint slides
  * `openai` (optional) – Advanced summarization with GPT
  * `nltk` / `spacy` – Natural Language Processing

---

## 🔧 Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/youtube-to-ppt.git
   cd youtube-to-ppt
   ```

2. **Create and activate virtual environment (optional but recommended)**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Usage

### Basic Command:

```bash
python main.py --url "https://www.youtube.com/watch?v=example"
```

### Optional Parameters:

* `--frames` : Include visual slides from key video frames
* `--lang en` : Specify language for transcript (default: `en`)
* `--gpt` : Use OpenAI GPT model for summarization (requires API key)

### Output:

* A `.pptx` file is generated in the `output/` folder with the same name as the video title.

---

## 📁 Project Structure

```
youtube-to-ppt/
├── main.py
├── downloader.py
├── transcriber.py
├── summarizer.py
├── ppt_generator.py
├── requirements.txt
└── README.md
```

---

## 📌 Use Cases

* 📚 Academic presentations from educational YouTube content
* 🧑‍🏫 Teacher aids and lecture summaries
* 💼 Business summaries from webinars
* 👩‍💻 Content creation and repurposing

---

## ⚠️ Limitations

* Transcription accuracy may vary depending on audio quality
* Long videos may require processing time and memory
* GPT-based summarization requires OpenAI API access

---

## 📈 Future Improvements

* Add GUI support using Tkinter or PyQt
* Support for bulk video processing
* Custom slide design templates
* Real-time progress visualization

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or pull request to improve this tool.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**\Ayaan Sheikh**
Founder, \[Worklyft]
[LinkedIn](https://linkedin.com/in/mdayaansheikh) | [GitHub](https://github.com/Ayaan-sk) | [Portfolio](https://yourwebsite.com)

---

Let me know if you’d like to tailor it further to include API usage, UI, or deployment instructions!
