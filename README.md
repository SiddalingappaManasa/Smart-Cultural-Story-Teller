Smart Cultural Story Teller 🎭📚
📌 Overview

Smart Cultural Story Teller is an AI-powered storytelling system designed to preserve and present cultural stories in an engaging, human-like manner. Unlike generic story generators, this project focuses on cultural context, emotional expression, and multimodal storytelling (text, images, and audio).
The system generates stories based on cultural themes, enhances them with AI-generated visuals, narrates them using text-to-speech, and adds emotional cues through facial expression analysis—making storytelling more immersive and accessible.

❓ Problem Statement

Traditional cultural stories are:
Slowly disappearing due to lack of digital preservation
Presented in static text formats with low engagement
Not accessible to younger audiences or non-native readers
There is a clear need for a modern, interactive, AI-driven system that keeps cultural storytelling alive while respecting its essence.

🚀 Features

🧠 AI-based Story Generation with cultural prompts
🖼️ Image Generation using Clipdrop API (Hugging Face as fallback)
🔊 Text-to-Speech Audio Narration using pyttsx3
😊 Facial Expression Mapping using MediaPipe Face Landmark Detection
🔄 Fallback & Reliability Mechanisms for external APIs
🎯 Modular architecture for easy future expansion

🛠️ Tech Stack

Programming Language: Python
Story Generation: Large Language Models (LLMs)
Image Generation: Clipdrop API, Hugging Face
Audio Generation: pyttsx3
Facial Expression Detection: MediaPipe Face Mesh
Development Environment: Jupyter Notebook

🧩 System Architecture (High-Level)

User provides a cultural theme or prompt
LLM generates a culturally contextual story

Media Engine:

Generates images aligned with story scenes
Converts story text into narrated audio
Facial landmark detection maps emotional expressions
Final output delivers a multimodal storytelling experience

▶️ How to Run
# Clone the repository
git clone https://github.com/your-username/smart-cultural-story-teller.git

# Navigate to project directory
cd smart-cultural-story-teller

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook storyteller_notebook.ipynb

📊 Use Cases

Cultural education platforms
Digital museums and archives
Storytelling for children and language learners
AI-driven ed-tech applications

🔮 Future Enhancements

Multilingual storytelling support
Emotion-aware voice modulation

Web-based UI with real-time interaction

Personalized stories based on user age and region
