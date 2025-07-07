# BrieflyMeet – AI-powered Meeting Summarizer

BrieflyMeet is an intelligent meeting summarization tool built using NLP and transformer models. It transforms long meeting transcripts into concise, readable summaries — ideal for morning briefings, project reviews, or business updates.

## Features:

#### Audio-to-Text:
Convert recorded meeting audio into clean, readable transcripts using speech-to-text models (e.g., Whisper, Google STT).

#### Meeting Summarization:
Generate concise summaries of lengthy transcripts using Transformer models like `facebook/bart-large-cnn`.

#### Actionable Task Extraction:
Detect tasks and responsibilities assigned during the meeting using keyword-based and NLP-based pattern recognition.

#### Slack Integration:
Automatically send to-do lists to your team's Slack channel using incoming webhooks — keeping everyone aligned and accountable.

### git clone https://github.com/urjamehta21/briefly-meet.git
cd briefly-meet
pip install -r requirements.txt

If not then install it manually:
pip install transformers openai-whisper nltk spacy requests

#### Run the Notebook
jupyter notebook brieflymeet.ipynb

