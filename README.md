# LangChain Demo with OpenAI API

This project is a demo application showcasing the integration of [LangChain](https://www.langchain.com/) and OpenAI's GPT model using the Streamlit framework. The app provides a chatbot interface that responds to user queries.

## Features

- **Streamlit Interface**: Simple and interactive UI for user input.
- **LangChain**: Leverages LangChain for prompt management and chaining.
- **OpenAI GPT**: Utilizes `gpt-3.5-turbo` for generating responses.
- **Environment Variables**: API keys and configurations managed securely using `.env` files.

---

## Setup and Installation

Follow these steps to set up and run the project:

### Prerequisites

- Python 3.8 or higher
- [pip](https://pip.pypa.io/en/stable/installation/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
Create and activate a virtual environment:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install the required packages:

bash
Copy
Edit
pip install -r requirements.txt
Create a .env file in the root directory and add your API keys:

makefile
Copy
Edit
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
Usage
Run the Streamlit application:

bash
Copy
Edit
streamlit run app.py
Open the app in your browser at http://localhost:8501.

Input a topic or query, and the chatbot will provide a response.

Project Structure
bash
Copy
Edit
.
├── app.py              # Main application file
├── .env                # Environment variables
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
Dependencies
LangChain
Streamlit
Python Dotenv
[OpenAI](https://pypi.org/project/openai
