# Youtube-Video-And-Website-Url-Summarization-groq-api
# Youtube Video and Website URL Summarization with Groq API

This project demonstrates how to use **Groq API** along with **LangChain** to summarize content from **YouTube videos** or **websites**. By leveraging the Groq LLM model, it processes the content and generates concise summaries.

---

## Project Overview

This application uses **Streamlit** as the user interface and **Groq's ChatGroq API** for content summarization. The user provides a URL (YouTube video or website), and the system extracts and summarizes the content into a concise 300-word summary.

### Key Features:
- **Summarize YouTube videos**: Extracts the video transcript and provides a summary.
- **Summarize Website content**: Extracts text from a website and generates a summary.
- **Powered by Groq's LLM**: Uses Groq's advanced AI model (`Gemma-7b-It`) for text summarization.
- **Streamlit Interface**: A user-friendly web interface for interacting with the application.

---

## Project Structure

1. **app.py**  
   The main application built using **Streamlit** where users input the URL (YouTube video or website) and get the summarized content.

2. **LangChain Integration**  
   This handles text summarization, utilizing the **ChatGroq API** model (`Gemma-7b-It`) to generate summaries.

3. **Validators and Loaders**  
   Includes URL validation and content loading logic to fetch content from YouTube or websites.

4. **Prompt Template**  
   A custom prompt template used to instruct the model on how to summarize the content.

---

## Prerequisites

1. **Python 3.7+**  
   Ensure that Python 3.7 or a later version is installed.

2. **Anaconda/Miniconda (Optional but recommended)**  
   It helps to manage the environment and dependencies easily.

3. **Groq API Key**  
   You will need an API key from **Groq** to access the LLM services.

4. **Streamlit**  
   This project uses **Streamlit** for creating the web interface.

---

## Installation and Setup

1. **Clone the Repository**  
   Clone this project to your local machine:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
