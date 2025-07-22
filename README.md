# hegemon.ai
hegemon.ai is a conversational chatbot application designed to assist users in exploring and learning about multifaceted topics ranging from historical analysis to current geopolitical trends, global economics, and international relations. Built with a focus on domain-specific knowledge, the chatbot leverages modern AI and web technologies to create an engaging user experience for research, education, or personal curiosity.

## Key Features

- Conversational interface for history, geopolitics, economy, and more
- Web app with live chat experience
- Specialized dataset or prompt engineering to focus dialogue on global affairs
- Extendable structure for adding domains or customizing responses

## Repository Structure
```text
/static
    hegemon_image.jpeg      # Visual asset for the web application
    hegemon.css             # Custom CSS for main theme
    style.css               # Additional styling

/templates
    chat_page.html          # Main chat page template
    index.html              # Landing or introductory page

app.py                      # Main Flask application (backend)
hegemon_chatbot.py          # Core chatbot logic and prompt handling
requirements.txt            # Python dependencies
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Shaan2522/hegemon.ai.git
cd hegemon.ai
```

2. Create and activate a virtual environment (optional):
```bash
python -m venv venv
source venv/bin/activate   # On Linux/macOS
venv\Scripts\activate      # On Windows
```

3. Install required dependencies:
```bash
python app.py
```

4. Run the Flask application:
```bash
python app.py
```

## Technology Stack

| Component | Description |
|-----------|-------------|
| Python | Main programming language |
| Flask | Web application microframework |
| HTML/CSS | Frontend templates and styling |
| JavaScript | for interactivity in frontend |
| AI/LLM | Integration For chatbot intelligence (Gemini API) |

