# Retrivex

**A Java-based Desktop Document Search Engine**

Retrivex is a desktop application built using Java and JavaFX that allows users to search through TXT, PDF, and DOCX files from a single interface. Instead of manually opening documents one by one, the application indexes their contents and retrieves the most relevant results based on the search query using Information Retrieval techniques.

---

## About the Project

Finding information across multiple documents can be time-consuming, especially when files are stored in different formats. Retrivex was developed to simplify this process by creating a searchable index of documents and ranking the results according to their relevance.

The project supports text files, PDF documents, and Microsoft Word documents. It extracts textual content, preprocesses it, builds an inverted index, and uses the TF-IDF algorithm to return relevant search results. The application also provides document previews, keyword highlighting, and contextual snippets through a simple JavaFX interface.

---

## Features

- Search across TXT, PDF, and DOCX documents
- Fast document retrieval using Inverted Indexing
- TF-IDF based relevance ranking
- Keyword highlighting
- Contextual search snippets
- Document preview inside the application
- JavaFX desktop interface
- Multi-format document support
- Local document indexing without requiring an internet connection

---

## Technology Stack

| Programming Language | Java |
| GUI Framework | JavaFX |
| PDF Processing | Apache PDFBox |
| DOCX Processing | Apache POI |
| IDE | IntelliJ IDEA |
| Version Control | Git |
| Repository Hosting | GitHub |

---

## Concepts Used

- Information Retrieval
- Inverted Index
- TF-IDF Ranking
- Tokenization
- Text Normalization
- File Handling
- HashMap
- ArrayList
- Java Collections Framework
- Event Handling
- Object-Oriented Programming

---

## Project Structure

```text
Retrivex
│
├── src/
│   └── Main.java
│
├── data/
│   ├── sample files
│
├── screenshots/
│
├── docs/
│
├── README.md
└── .gitignore
```

---

## How It Works

```
User Uploads Documents
          │
          ▼
Extract Text from Files
          │
          ▼
Normalize & Tokenize Text
          │
          ▼
Create Inverted Index
          │
          ▼
User Enters Search Query
          │
          ▼
Calculate TF-IDF Scores
          │
          ▼
Rank Matching Documents
          │
          ▼
Display Results with Snippets
```

---

## Screenshots

### Home Screen

> <img width="1920" height="1080" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/ebe5524c-dbdf-4217-bbb6-003f179895da" />
> <img width="1920" height="1080" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/69274800-84b7-4f27-81b9-12e3647b71fc" />

---

### Search Results

> <img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/279a8b9a-79db-4d51-902d-b0235ba44897" />
> <img width="1920" height="1080" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/a91c07f6-03c9-4bef-89ff-5d8b928a0da6" />
> <img width="1920" height="1080" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/980a3395-683b-40b8-b92f-1934206d3e8f" />


---


## Getting Started

### Prerequisites

- Java JDK 21 or above
- JavaFX SDK
- IntelliJ IDEA (Recommended)

### Clone the Repository

```bash
git clone https://github.com/bhttr1769/Retrivex-Document-Search-Engine.git
```

### Run the Project

1. Open the project in IntelliJ IDEA.
2. Configure the JavaFX SDK if it is not already configured.
3. Open `Main.java`.
4. Run the application.
5. Upload documents and start searching.

---

## Future Improvements

- Semantic search using AI models
- Database-backed indexing
- Support for PPT and Excel files
- Automatic folder monitoring
- Cloud synchronization
- Web-based version
- Search filters and advanced query options

---

## Author

**Parth Bhattar**

B.Tech Computer Science Engineering

JECRC University

GitHub: https://github.com/bhttr1769

---

## License

This project is intended for educational and learning purposes.
