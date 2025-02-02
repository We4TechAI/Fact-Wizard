# 🧙‍♂️ FactWizard: AI Knowledge Explorer

FactWizard is an AI-powered fun fact generator that uses the Groq API to create engaging and surprising facts about various topics. Built with Streamlit, this interactive web application makes learning fun and magical!

![FactWizard Demo](assets/banner.py)

## ✨ Features

- Generate fun facts about specific topics or random subjects
- Clean, intuitive user interface with magical theme
- Real-time fact generation using Groq's LLaMA model
- Easy-to-use topic selection
- Share functionality for interesting facts
- Docker support for easy deployment

## 🚀 Quick Start

### Local Installation

1. Clone the repository:
```bash
git clone https://github.com/We4TechAI/Fact-Wizard.git
cd Fact-Wizard
```

2. Create and activate a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the project root:
```bash
GROQ=your_groq_api_key_here
```

5. Run the application:
```bash
streamlit run fact_wizard.py
```

### 🐳 Docker Deployment

1. Build the Docker image:
```bash
docker build --tag fact_wizard:latest .
```

2. Run the container:
```bash
docker run -d --name fact_wizard -p 8501:8501 fact_wizard:latest
```

Access the application at `http://localhost:8501`

## 📁 Project Structure

```
FactWizard/
├── fact_wizard.py        # Main application file
├── requirements.txt      # Python dependencies
├── Dockerfile           # Docker configuration
├── .env                 # Environment variables (create this)
├── .gitignore          # Git ignore file
└── README.md           # Project documentation
```

## 📋 Dependencies

- Python 3.8+
- Streamlit
- Groq API
- python-dotenv
- Docker (optional)



## 🛡️ Environment Variables

Create a `.env` file with your Groq API key:
```env
GROQ=your_groq_api_key_here
```

## 🌟 Usage

1. Select a topic from the sidebar dropdown menu
2. Click "Cast Knowledge Spell! ✨" to generate a fact
3. Use "Cast Another Spell" to generate more facts
4. Share interesting facts using the share button

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Groq API for providing the LLM capabilities
- Streamlit for the amazing web framework
- The open-source community for inspiration and support

## 📧 Contact

For questions or feedback, please open an issue on the GitHub repository.

---
Made with 🪄 by [We4TechAI](https://github.com/We4TechAI)
