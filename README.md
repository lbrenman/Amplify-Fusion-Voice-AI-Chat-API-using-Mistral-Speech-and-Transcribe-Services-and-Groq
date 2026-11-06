# Amplify Fusion Voice AI Chat API using Mistral Speech and Transcribe Services and Groq

An Amplify Fusion Voice AI Chat REST API that leverages [Mistral speech and transcribe services](https://mistral.ai/solutions/speech/) and [Groq](https://groq.com/).

It exposes one main POST methods:

/voice-ai-chat - transcribes MP3 or WAV audio to text sends to LLM and turns the text response into MP3 or WAV audio returned as Base64 encoded string. Voice and conversationId can be configured.

The API leverage Amplify Fusion Mistral Transcribe/Speech and OpenAI connectors

Also included is a sample web app for testing the API

## Getting Started

* Import Fusion project in Manager
* Configure the connectors
* Activate the API