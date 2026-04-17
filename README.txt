DIO-Whisper
===========

A multi-language voice assistant built in Google Colab that records your voice,
transcribes it with OpenAI's Whisper, sends the text to GPT-4, and reads the
response aloud using gTTS — all in a single notebook.

Features:
- Audio recording via browser (MediaStream Recording API)
- Speech-to-text with OpenAI Whisper
- Natural language responses powered by GPT-4
- Conversation history for context-aware replies
- Text-to-speech output with gTTS (multi-language support)
- Secure API key handling via Google Colab Secrets
