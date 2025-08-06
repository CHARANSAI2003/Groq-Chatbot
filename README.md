# Groq Chatbot with LLaMA3-70B

A simple yet powerful command-line chatbot built using the Groq API and LLaMA3-70B model. This interactive chatbot maintains conversation history and provides intelligent responses using state-of-the-art language model capabilities.

## 🌟 Features

- **Interactive Chat Interface**: Command-line based conversation with the AI
- **Conversation Memory**: Maintains chat history throughout the session
- **LLaMA3-70B Integration**: Powered by Groq's fast inference API
- **Easy Setup**: Simple installation and configuration process
- **Customizable Parameters**: Adjustable temperature for response creativity

## 🚀 Demo

The chatbot can help with various tasks including:
- Code generation and explanation (Python, JavaScript, etc.)
- General question answering
- Technical problem solving
- Creative writing assistance

**Example Interaction:**
🤖 Groq Chatbot (LLaMA3-70B). Type 'exit' to quit.

You: Even or odd program in Python
Bot: Here is a simple Python program that determines whether a given integer is even or odd:

def is_even_or_odd(n):
if n % 2 == 0:
return "Even"
else:
return "Odd"

Test the function
num = int(input("Enter an integer: "))
print(is_even_or_odd(num))


## 📋 Prerequisites

- Python 3.7 or higher
- Groq API key (get yours at [Groq Console](https://console.groq.com))

## 🔧 Installation

1. **Clone the repository:**

git clone https://github.com/CHARANSAI2003/groq-chatbot.git
cd groq-chatbot


2. **Install required packages:**


3. **Set up your API key:**
- Replace the API key in the notebook with your own Groq API key
- **Important**: Never commit your actual API key to version control

## 🎯 Usage

### Running as Jupyter Notebook

1. Launch Jupyter Notebook:

2. Open `groq_chatbot.ipynb`

3. Replace the API key with your own:

client = OpenAI(
api_key="your-groq-api-key-here",
base_url="https://api.groq.com/openai/v1"
)


4. Run all cells and start chatting!

### Converting to Python Script

You can also convert the notebook to a standalone Python script:

jupyter nbconvert --to script groq_chatbot.ipynb
python groq_chatbot.py


## ⚙️ Configuration

The chatbot uses the following default settings:
- **Model**: `llama3-70b-8192`
- **Temperature**: `0.7` (controls response creativity)
- **Base URL**: `https://api.groq.com/openai/v1`

You can modify these parameters in the code to customize the behavior.

## 🔒 Security

- **API Key Management**: Store your API key securely and never commit it to version control
- **Rate Limits**: Be aware of Groq API rate limits and usage policies
- **Data Privacy**: Conversation data is sent to Groq's servers for processing

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Project Structure

groq-chatbot/
│
├── groq_chatbot.ipynb # Main Jupyter notebook
├── README.md # Project documentation


## 🐛 Troubleshooting

**Common Issues:**

- **API Key Error**: Make sure your Groq API key is valid and has sufficient credits
- **Connection Error**: Check your internet connection and Groq API status
- **Import Error**: Ensure the OpenAI package is installed (`pip install openai`)

## 📚 Learn More

- [Groq API Documentation](https://console.groq.com/docs)
- [LLaMA3 Model Information](https://llama.meta.com/llama3/)
- [OpenAI Python Library](https://github.com/openai/openai-python)


## 🏷️ Tags

`python` `chatbot` `groq` `llama3` `ai` `machine-learning` `jupyter-notebook` `openai-api`

## 👤 Author

**Charan Sai Batthala**
- GitHub: [@CHARANSAI2003](https://github.com/CHARANSAI2003)
- LinkedIn: [bathala-charansai-2003](https://www.linkedin.com/in/bathala-charansai-2003/)
- Email: charansai2003110@gmail.com

## ⭐ Show Your Support

If you found this project helpful, please give it a ⭐ on GitHub!

---

*Last updated: August 2025*
