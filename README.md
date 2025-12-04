Information Retrieval System
Local Information Retrieval System

This repository contains a local Information Retrieval (IR) system implemented in Python. It supports preprocessing, indexing, BM25-based retrieval with enhancements, query expansion, and ranking of documents with recency and overlap bonuses.

Project Structure
Homework-Assignment-3/
│
├── code.ipynb              # Main Jupyter Notebook containing IR system implementation
├── preprocessed_data.pkl   # Preprocessed dataset with headings, articles, and tokens
├── inverted_index.pkl      # Inverted index of the dataset for efficient retrieval
├── dates_min_max.pkl       # Min and max dates used for recency scoring
├── README.md               # This file
├── requirements.txt        # Python dependencies
└── .gitignore              # Git ignore file to exclude unnecessary files/folders (e.g., venv)

Setup Instructions
1. Clone the Repository
   
git clone https://github.com/Myz222/IR-System-Assignment3.git
cd IR-System-Assignment3

3. Create and Activate Virtual Environment

Windows

python -m venv venv
venv\Scripts\activate


Linux/Mac

python3 -m venv venv
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt


Required Libraries (highlighting non-Bash/terminal things):
os (built-in)
pandas
nltk
math (built-in)
pickle (built-in)
itertools (built-in)

4. Run the IR System
Open code.ipynb in Jupyter Notebook or VS Code and execute cells sequentially.








