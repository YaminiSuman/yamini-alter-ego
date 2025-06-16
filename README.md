# Yamini's Alter Ego – Interactive AI Chat Agent

An intelligent, chat-based AI agent built with Python and Gradio that represents me on my personal website. It answers questions about my skills, experience, and background, acting as a real-time interactive assistant.

## Key Features

* **OpenAI Function Calling for Intent Detection & Actions**
  The agent understands user intent beyond simple chat and can take meaningful actions.

  * For example, if you express interest in collaboration, it will prompt for your email and trigger a background function that sends me an instant push notification.
  * If it encounters a question it cannot answer, the agent logs it for me to review and improve later.

* **Experience Summarization**
  Summarizes my professional experience by referencing my LinkedIn PDF and a custom summary file, providing concise and relevant responses.

* **Real-Time Alerts**
  Sends immediate notifications via the Pushover API when important follow-ups or actions are triggered.

* **Deployment & UI**
  Hosted on [Hugging Face Spaces](https://huggingface.co/spaces/yamini-suman/yamini-ai-agent) with a clean and user-friendly interface that automatically handles user messages.

## Who Is It For?

Whether you're a recruiter, potential collaborator, or just curious, you can chat with my AI assistant. It knows when to bring me into the conversation and helps streamline communication efficiently.

## Tech Stack

* Python
* Gradio for the web interface
* OpenAI API (with function calling)
* Pushover API for push notifications
* Hosted on Hugging Face Spaces

## Usage

1. Visit the deployed app here: [Yamini's Alter Ego on Hugging Face](https://huggingface.co/spaces/yamini-suman/yamini-ai-agent)
2. Start chatting with the AI to learn about my skills and experience or discuss potential collaboration.
3. The agent will automatically handle your inputs and notify me when necessary.

## Development

If you want to run the project locally or contribute:

```bash
git clone <repository-url>
cd alter-ego
pip install -r requirements.txt
python app.py
```

## Future Improvements

* Expand knowledge base with more documents and data sources
* Improve intent recognition with additional training
* Add multi-language support

