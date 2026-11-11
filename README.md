# 🌍 Multilingual AI Voice Assistant

An AI-powered multilingual voice assistant built using **Python, Streamlit, Whisper, and FLAN-T5**. It allows users to communicate in different languages through voice or text and receive AI-generated responses in their original language.

## 🚀 Project Overview

The Multilingual AI Voice Assistant combines Speech Recognition, Natural Language Processing (NLP), Machine Learning, and Text-to-Speech technology.

Users can:
- Record voice messages using a microphone.
- Enter messages through text chat.
- Automatically detect the input language.
- Translate messages into English.
- Generate AI-powered responses.
- Translate responses back into the user's language.
- Listen to responses using voice output.
- View and manage conversation history.

## ✨ Features

- **Speech Recognition:** Converts spoken language into text using OpenAI Whisper.
- **Language Detection:** Identifies the user's language using LangDetect.
- **Language Translation:** Translates text using Google Translator.
- **AI Response Generation:** Generates responses using FLAN-T5.
- **Text-to-Speech:** Converts AI responses into audio using gTTS.
- **Voice and Text Interaction:** Supports both microphone and text-based communication.
- **Conversation History:** Stores conversations during the active session.
- **Interactive UI:** User-friendly Streamlit interface with custom CSS styling.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Web application interface |
| OpenAI Whisper | Speech-to-text |
| FLAN-T5 | AI response generation |
| Transformers | Loading pretrained AI models |
| PyTorch | Deep learning framework |
| Librosa | Audio processing and resampling |
| SoundFile | Reading audio files |
| LangDetect | Language detection |
| Deep Translator | Text translation |
| gTTS | Text-to-speech |
| NumPy | Numerical operations |

## 📂 Project Structure

```text
Multilingual_AI_Voice_Assistant/
│
├── app.py
│   └── Streamlit user interface
│
├── assistant.py
│   └── AI models and processing functions
│
├── requirements.txt
│   └── Required Python libraries
│
├── README.md
│   └── Project documentation
│
└── venv/
    └── Python virtual environment
```

## ⚙️ Installation and Setup

### Step 1: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the project folder

```bash
cd Multilingual_AI_Voice_Assistant
```

### Step 3: Create a virtual environment

Python 3.11 is recommended.

```bash
py -3.11 -m venv venv
```

### Step 4: Activate the environment

For Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### Step 5: Install PyTorch

```bash
pip install torch torchaudio --index-url https://download.pytorch.org/whl/cpu
```

### Step 6: Install dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

Start the Streamlit application using:

```bash
python -m streamlit run app.py
```

Open the local URL displayed in your terminal, usually:

```text
http://localhost:8501
```

## 🔄 System Workflow

1. User provides voice or text input.
2. Whisper converts voice input into text.
3. LangDetect identifies the input language.
4. Deep Translator translates the message into English.
5. FLAN-T5 generates an AI response.
6. Deep Translator translates the response into the original language.
7. gTTS converts the response into speech.
8. Streamlit displays the text and audio output.

## 🧠 AI Models

**1. Whisper Small**
- Model: `openai/whisper-small`
- Used for multilingual speech recognition.

**2. FLAN-T5 Base**
- Model: `google/flan-t5-base`
- Used for natural-language response generation.

Both models are downloaded automatically when the application is first launched.

## 📌 Requirements

- Python 3.11 recommended.
- Internet connection for model downloads, translation, and voice generation.
- Microphone for voice interaction.
- Sufficient RAM and storage for AI models.

## 🔮 Future Enhancements

- Add more language support.
- Improve response accuracy.
- Add conversation export functionality.
- Integrate advanced conversational AI models.
- Add user authentication.
- Deploy the application online.

## 👨‍💻 Project

**Project Name:** Multilingual AI Voice Assistant

**Domain:** Artificial Intelligence | Natural Language Processing | Deep Learning

**Built With:** Python, Streamlit, Whisper, FLAN-T5 and PyTorch.

---

⭐ If you find this project interesting, consider giving the repository a star!

**Note:** This project uses online translation and text-to-speech services. Their availability and language support may vary.