# ContentSummarization

This project is a content summarization tool that uses **Streamlit**, **LangChain**, and **Groq API** to generate concise summaries of content from YouTube videos and website URLs. The app provides a user-friendly interface where users can input URLs to receive quick, digestible summaries without needing to consume the entire content.

## Features

- **Summarization from YouTube and Websites**: Automatically generates summaries from YouTube videos or any website URL.
- **Customizable Prompt**: Uses a 300-word summary prompt for consistent and informative results.
- **Real-Time Display**: Summarized content is displayed in real-time within the Streamlit app.
- **User Authentication**: Accepts Groq API key input via a secure password field in the sidebar.
- **Error Handling**: Includes robust error handling and URL validation for seamless user experience.

## Technologies Used

- **Streamlit**: For creating the web app interface.
- **LangChain**: Framework for handling prompts and language model interactions.
- **Groq API**: For processing and generating summaries with language models.
- **Python**: Core programming language used.

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/content-summarization-tool.git
   cd content-summarization-tool
   ```

2. **Install the dependencies**:
   Ensure you have Python 3.8+ installed. Then, run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up the Groq API Key**:
   - Obtain an API key from [Groq](https://groq.com).
   - Set the `GROQ_API_KEY` environment variable in your shell, or input it manually in the sidebar when launching the app.

4. **Run the Streamlit app**:
   ```bash
   streamlit run app.py
   ```

## Usage

1. **Enter the URL**: Paste the YouTube or website URL into the URL input box.
2. **Enter the API Key**: Input your Groq API key in the sidebar if not already set as an environment variable.
3. **Summarize**: Click the **"Summarize the Content from YT or Website"** button to get a summary of the content.

