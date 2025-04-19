# LLM Hacker - Adversarial Emulation Tool

An interactive tool for emulating hacking methodologies with LLMs, utilizing the free API from OpenRouter.ai.

🔧 Recent Improvements for the LLM

Refined the GUI experience by removing cluttered or unnecessary UI elements for a cleaner, more mission-focused interface.

Streamlined prompt construction for faster, more direct adversarial emulation responses.

Aggressive mode is now enforced by default, improving response quality and reducing model hesitation.

Removed “Standard” operation mode to keep all interactions focused on realism, technical detail, and offensive tradecraft.

Replaced legacy banners and added a customized branding header and footer for clarity and polish.

Initial model remains deepseek/deepseek-chat-v3-0324:free, but...

⚠️ Upcoming switch: Evaluating and preparing transition to mistralai/mixtral-8x7b:free, a significantly more effective model for red team simulation, malware enhancement, and bypass strategy development.

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
