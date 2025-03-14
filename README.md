**Brainlox Course Finder Chatbot**  

This is an AI-powered chatbot that helps users find relevant courses from Brainlox based on their queries. It uses LangChain, Google Gemini AI, FAISS, and Gradio to fetch and recommend courses.  

**Features**  

- Fetches course data from the Brainlox website  
- Uses FAISS vector search for fast recommendations  
- Embeds text using Google Gemini AI embeddings  
- Simple Gradio interface for user interaction  

**Tech Stack**  

- Python  
- LangChain  
- FAISS (Vector Database)  
- Google Gemini AI (Embeddings & Chat)  
- Gradio (for UI)  

**Setup & Installation**  

1. Clone the Repository  

   ```bash
   git clone https://github.com/yourusername/brainlox-chatbot.git
   cd brainlox-chatbot
   ```

2. Install Dependencies  

   ```bash
   pip install langchain faiss-cpu google-generativeai gradio
   ```

3. Set up API Key  

   Replace `"API KEY"` in the script with your Google Gemini API key.  

   ```python
   os.environ["GOOGLE_API_KEY"] = "your_api_key_here"
   ```

4. Run the Chatbot  

   ```bash
   python chatbot.py
   ```

   Or, if using Google Colab, run the notebook cells.  

**Usage**  

Enter a query (e.g., "Do you offer cloud computing training?"). The chatbot retrieves relevant course details. If no relevant course is found, it responds accordingly.  

**Contributing**  

Feel free to fork the repo, improve the chatbot, and submit a pull request.  

**License**  

MIT License - Free to use and modify.  
