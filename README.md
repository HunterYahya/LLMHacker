# LLM Hacker - Adversarial Emulation Tool

An interactive tool for emulating hacking methodologies with LLMs, utilizing the free API from OpenRouter.ai.

🔧 Recent Improvements for the LLM

Refined the GUI experience by removing cluttered or unnecessary UI elements for a cleaner, mission-focused interface.

Streamlined prompt construction to enable faster, more direct adversarial emulation with better response control.

Aggressive mode is now the default, eliminating delays and improving model assertiveness and tradecraft relevance.

Deprecated “Standard” operation mode to ensure all interactions stay technically realistic and offensive-oriented.

Replaced legacy banners with custom branding and a redesigned footer for a professional, operator-friendly visual.

Current model: deepseek/deepseek-chat-v3-0324:free

⚠️ Planned upgrade: Actively evaluating a transition to mistralai/mixtral-8x7b:free — a significantly more capable model for red teaming, malware enhancement, and bypass technique generation.

## 🚀 Features

- Interactive chat interface for technical adversarial emulation
- Supports multiple attack phases based on the MITRE ATT&CK framework
- Detailed logging of all operations
- Export functionality for operation data

## 📋 Prerequisites

- Python 3.6+
- OpenRouter.ai free API key
- Internet connection

## ⚙️ Installation

### Step 1: Clone the repository
```bash
git clone https://github.com/yourusername/llm-hacker.git

cd llm-hacker

Step 2: Set up a virtual environment

Using Git Bash (recommended):
bash# Create virtual environment
python -m venv venv

# Activate it
venv/Scripts/activate

# Install required packages
pip install streamlit requests

🔧 Configuration
Open llmhacker.py and update the API key and model selection:

Find lines 61-67 in the code
Replace the default API key with your OpenRouter API key
Choose your preferred model (default is DeepSeek V3 0324 FREE)

🏃‍♂️ Running the Application
streamlit run llmhacker.py
The application will open in your default web browser.
💡 Recent Improvements

Performance optimization: Removed adversary profiles to reduce latency and improve response time
Streamlined interface: Focused on core functionality for better user experience
Updated system prompts: Enhanced response quality for technical operations

⚠️ Disclaimer
This tool is for educational purposes and legitimate security testing only. Always use responsibly and ethically in authorized environments.
📝 Feedback
This is my first GitHub project, so I would appreciate any feedback, suggestions for improvement, or comments!
