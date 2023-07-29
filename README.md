# pdfs-chat-bot
Upload multiple PDF documents and chat with an AI bot 


Interactive Chatbot with Multiple PDFs
This interactive chatbot allows users to have natural language conversations with it based on the content extracted from multiple PDF documents. It is designed to be used in conjunction with the documentation scraping project available on GitHub. First, the scraping project extracts text from various documentation sources and converts it to PDF. The resulting PDFs can then be uploaded to this chatbot, enabling users to interact with the content effectively.

Usage Instructions
Scrape Documentation and Convert to PDF: First, utilize the documentation scraping project to gather the required PDFs. Ensure you have the necessary PDF documents ready for upload.

API Key Requirements: To use this chatbot, you will need an OpenAI API key. Alternatively, you can also use the Hugging Chat API key for the language models and vector similarity search. Ensure you have the API key ready before running the chatbot script.

Install Dependencies: Make sure you have the required dependencies installed. You can install them using the following command:

bash
Copy code
pip install streamlit dotenv PyPDF2 langchain htmlTemplates
Run the Chatbot: Run the chatbot script chatbot.py using the following command:

bash
Copy code
streamlit run chatbot.py
Chat with the Bot: Once the chatbot is up and running, you can start asking questions related to the uploaded PDFs. The chatbot leverages advanced language models and vector similarity search to provide relevant and informative responses based on the content in the PDFs.

How it Works
The chatbot's functionality is powered by the Conversational Retrieval Chain, which uses the language models and vector stores created from the PDF text chunks. The chatbot employs natural language processing techniques to understand user queries and provides responses based on the uploaded PDF documents.

Disclaimer
Please note that the chatbot's responses are generated based on the content of the uploaded PDFs. It is crucial to ensure that the documents are accurate and up-to-date to get reliable responses from the chatbot.

License
This project is licensed under the MIT License. Feel free to modify, distribute, or use it for your needs.

Contact
If you have any questions or suggestions regarding this project, feel free to reach out to us. We appreciate your feedback and contributions.

Author: Assante Ahmad
Email: loukmanassante@outlook.com

By combining the capabilities of the documentation scraping project and this interactive chatbot, users can conveniently explore and interact with the content of multiple PDF documents using natural language queries. Enjoy exploring and learning with this versatile tool!
