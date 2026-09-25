Python & AI Engineering Learning Journey 🚀

Welcome to my repository! This project serves as a comprehensive log of my progress learning Python from the ground up, moving through data structures, file handling, JSON serialization, and finally stepping into AI Engineering with vector embeddings and local vector databases (ChromaDB and Google Gemini API).

📂 Repository Structure & What's Inside

1. Python Basics & Fundamentals

Hello.py — My very first step into Python, printing introductory statements as an aspiring AI Engineer.

variables.py — Practice with basic variable types (strings, integers) and formatted strings (f-strings).

condition.py — Conditional logic (if, elif, else) for age-based classification.

loops.py — Working with lists of dictionaries and iterating through data using for loops and custom functions.

2. Files & Data Serialization (json)

students_file.py — Writing and reading structured student data using standard plain text (.txt) files.

json_practice.py — Introduction to structured data storage using JSON (json.dump and json.load) with UTF-8 encoding support.

Project Day 1.py — A mini-project combining loops, conditional status mapping (grades to text descriptions), JSON file saving, and filtering loaded data.

3. AI Engineering & Vector Embeddings

first_embedding.py — Connecting to the Google Gemini API (gemini-embedding-001) to generate multi-dimensional vector embeddings for text, followed by implementing a mathematical Cosine Similarity function using numpy to compare semantic proximity.

chroma_test.py — Setting up a local vector database (ChromaDB) equipped with a custom Gemini embedding function to perform real local semantic search queries over documents.

🛠️ Tech Stack & Libraries

Python 3.x

Google GenAI SDK (google-genai)

ChromaDB (Local vector database)

NumPy (Mathematical operations and vector similarity)

Python-Dotenv (Secure environment variable management)

⚙️ Getting Started & Installation

Clone the repository:

git clone <your-repository-url>
cd <repository-folder>


Install the required packages:

pip install google-genai chromadb numpy python-dotenv


Set up your API Key (for AI scripts):

Create a .env file in the root directory.

Add your Google Gemini API key:

GEMINI_API_KEY="your_api_key_here"


Run any script:

python "Project Day 1.py"
python chroma_test.py
