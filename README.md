📚 Multi-PDF Reader Using Google Gemini and FAISS Index
This project is a powerful PDF reader that leverages the capabilities of the Google Gemini model for natural language understanding and the FAISS Index for efficient similarity search. It allows users to upload multiple PDF files, extract meaningful information, and query content interactively.

🚀 Features
Multi-PDF Upload: Supports multiple PDF files for simultaneous processing.
Natural Language Querying: Enables conversational querying of PDF content using Google Gemini.
Efficient Search: Employs FAISS Index for fast and accurate content retrieval.
Context Awareness: Maintains query context for meaningful and continuous interactions.
Embeddings Storage: Generates and stores embeddings for efficient query handling.
🛠️ Technologies Used
Google Gemini: For AI-powered natural language understanding.
FAISS: For indexing and similarity search of document embeddings.
Python Libraries:
PyPDF2 for PDF parsing.
sentence-transformers for embedding generation.
FAISS for similarity indexing.
Streamlit for building a user-friendly interface.

bash
Copy code

git clone https://github.com/your-username/multi-pdf-reader.git

cd multi-pdf-reader

Create a virtual environment:

bash

python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate     # For Windows
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Set up Google Gemini API:

Obtain API credentials from Google Gemini.
Add them to your environment variables or a .env file.
🖥️ Usage
Run the application:

bash
Copy code
streamlit run app.py
Upload your PDF files using the interface.

Interact with the documents by typing queries in the chatbox. The system will use Google Gemini to interpret your query and FAISS to fetch relevant content.

📊 Demo

🚧 Future Enhancements
Add support for real-time document updates.
Implement advanced summarization and keyword extraction features.
Integrate more embedding models for broader use cases.
🤝 Contributions
Contributions are welcome! Please open an issue or submit a pull request.

📄 License
This project is licensed under the MIT License. See the LICENSE file for more details.

🙋‍♂️ Author
Ojas Kelkar
