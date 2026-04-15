# Local-AI-Stack
A production-ready local AI stack featuring Ollama, Open WebUI, SearXNG for web search, and Kokoro TTS. Fully Dockerized with NVIDIA GPU support."
This project provides a complete, localized AI environment using Docker Compose. It integrates a Large Language Model (LLM) via Ollama, a user-friendly interface with Open WebUI, text-to-speech capabilities via Kokoro, and private web searching using SearXNG.

🚀 Features
Fully Local: Run models like Gemma 4 without external API dependencies.
GPU Accelerated: Configured for NVIDIA GPUs (RTX 3080 12GB tested) via WSL2.
Web Search: Integrated SearXNG for real-time information retrieval.
Voice Synthesis: High-quality TTS using the Kokoro engine.
🛠 Prerequisites
Before you begin, ensure you have the following installed:
Docker and Docker Compose
NVIDIA Container Toolkit (for GPU support)
WSL2 (if running on Windows)

🚀Installation & Setup
Follow these steps to get your local AI stack up and running.
1. Clone the Repository
First, clone this project to your local machine:
git clone https://github.com/cuccurese2010/Local-AI-Stack.git && cd Local-AI-Stack

3. Deploy with Docker Compose
Run the following command to download the images and start the containers in background mode:
docker compose up -d

4. Verify the Installation
Check if all containers are running:
docker ps
You should see ollama, open-webui, searxng, and kokoro-tts in the list.

5. Access the Web Interface
Once everything is running, open your browser and go to:
https://localhost
