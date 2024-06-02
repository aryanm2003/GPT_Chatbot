# GPT_Chatbot

This is a simple chatbot project created using the OpenAI and Streamlit packages in Python.

## Getting Started

Follow these instructions to get a copy of the project running on your local machine.

### Prerequisites

- Required packages listed in `requirements.txt`

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/aryanm2003/GPT_Chatbot.git
   cd GPT_Chatbot

2. **Open coding Ide and Install the packages in requirement.txt file**
    ```sh
    pip install -r requirements.txt

3. **Create an API key on OpenAI:**
- Go to the OpenAI API.
- Sign up and create your API key.

4. **Configure your API key:**
- Open the `config.json` file.
- Add your API key to the file:
  
  ```sh
  {
  "api_key": "YOUR_OPENAI_API_KEY"
  }

### Running the Project
1. Open a terminal and navigate to the project directory.
2. Run the Streamlit application:
  ```sh
  streamlit run src/main.py
```

3. Your chatbot will be published at the local host.

### Usage
- After running the above command, a local URL will be provided in the terminal.
- Open this URL in your web browser to interact with the chatbot.

### Built With
- OpenAI - Natural language processing API
- Streamlit - Web application framework
