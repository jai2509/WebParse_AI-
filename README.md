# WebParse AI

WebParse AI is a powerful web content extraction tool that retrieves and processes information from website URLs using advanced AI models. It leverages the **GROQ API** and **Hugging Face models** to analyze and summarize webpage content efficiently.

## Features
- **Extracts relevant content** from any given URL.
- **Uses AI-powered NLP** models for analysis and summarization.
- **Leverages GROQ API** for high-performance processing.
- **Hugging Face models** for text generation and enhancement.

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/jai2509/WebParse_AI-.git
cd WebParse_AI-
```

### 2. Set Up a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### 3. Install Dependencies
Ensure you have `pip` installed and then install the required packages:
```bash
pip install -r requirements.txt
```

### 4. Configure API Keys
Create a `.env` folder inside the project root directory and add an `.env` file with the following keys:
```ini
GROQ_API_KEY=your_groq_api_key
HUGGINGFACE_API_KEY=your_huggingface_api_key
```
Replace `your_groq_api_key` and `your_huggingface_api_key` with your actual API keys.

### 5. Run the Application
```bash
python main.py
```

## Usage
- Input a website URL.
- WebParse AI extracts and processes the content.
- The output includes structured information and summaries.

## Requirements
All dependencies are listed in `requirements.txt`. Key dependencies include:
```txt
requests
groq-api
huggingface_hub
beautifulsoup4
python-dotenv
```

## Contributing
Contributions are welcome! Feel free to submit pull requests or report issues.

## License
This project is licensed under the MIT License. See `LICENSE` for details.

## Contact
For queries or support, open an issue in the repository.

---
### Happy Parsing! 🚀
