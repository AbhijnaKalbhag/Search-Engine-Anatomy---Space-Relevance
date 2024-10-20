# 🌐 Contextual Search Engine

Welcome to the **Contextual Search Engine** project! This repository is designed to help you search for highly relevant information by understanding user queries and mapping semantic relationships intelligently. It leverages the power of natural language processing (NLP), knowledge graphs, and contextual spaces for accurate, personalized results.

## 🧠 Introduction

The **Contextual Search Engine** aims to provide more than traditional keyword-based searches by understanding the user's intent, relationships between keywords, and delivering results from a semantic and contextual perspective.

### 📜 Key Features:
1. **Keyword Extraction**: Uses various Python NLP libraries to extract relevant keywords from user queries.
2. **Semantic Relationship Mapping**: Constructs a graph of relationships between keywords, highlighting important connections.
3. **Knowledge Graph Construction**: Integrates semantic relationships with a knowledge graph, improving the depth and quality of search results.
4. **Contextual Mapping**: Results are mapped to predefined contextual spaces, enriching the user experience.
5. **Graph Pruning**: Unnecessary edges are pruned for efficiency, ensuring only meaningful relationships are preserved.

---

## 🗝️ Contextual Spaces

The contextual search engine operates using three distinct **contextual spaces**, inspired by ancient knowledge classification concepts:

1. **Pratyaksha (Direct/Immediate knowledge)**:
   - The system delivers results that **precisely match** the keywords in the user's query, ensuring the most immediate and direct retrieval of information.

2. **Anumana (Knowledge from inference)**:
   - The system infers what the user might be looking for by reasoning through the context of the query. It goes beyond keywords to **predict relevant information** based on the query's underlying meaning.

3. **Upamana (Knowledge through analogy or comparison)**:
   - The system recognizes patterns in user behavior or preferences, delivering **analogous or similar content** based on previous queries or similar searches by other users.

These contextual spaces help in refining the search results by mapping the query to the appropriate type of knowledge retrieval.

---

### 🕉️ Elements of Information Retrieval

To support these contextual spaces, the search engine employs three fundamental elements of information retrieval:

1. **Pradhana**:
   - Represents **all possible information**. This is the vast universe of data the system has access to, from which relevant results are retrieved.

2. **Prakriti**:
   - Refers to the **process** of organizing, searching, and retrieving relevant information from the **Pradhana**. It is the engine that powers the search.

3. **Maha-tattva**:
   - The **basic elements** that make up the information being found and analyzed. This includes keywords, metadata, relationships, and data structures that contribute to the final result set.

---

### ⚖️ Three Qualities of Information

The search engine also incorporates **three qualities** that define the nature of the information retrieved:

1. **Rajas (Passion/Activity)**:
   - Reflects the **dynamic, ever-changing nature** of search results, aligning with real-time trends and frequently updated content. This captures the active and fluid nature of trending or newly published data.

2. **Tamas (Ignorance/Inertia)**:
   - Represents **static or outdated information** that may still persist despite newer and more relevant content being available. This helps in understanding the inertia present in older or less relevant content.

3. **Sattva (Goodness/Harmony)**:
   - Signifies **accurate, relevant, and well-organized information** that aligns with the user's intent and provides a balanced, meaningful search experience. This quality emphasizes correctness and contextual harmony in the results.

---

By integrating these concepts of **contextual spaces**, **elements of information retrieval**, and the **three qualities**, the search engine offers a more comprehensive and **intuitive search experience** that goes beyond basic keyword matching.

## 🛠 Technologies Used

This project utilizes a variety of advanced libraries and algorithms to achieve effective keyword extraction, similarity measurements, and information retrieval. Below is an outline of the tools and technologies used:

### 🔧 Python Libraries
* **Keyword Extraction**:
    - `spaCy`: Used for advanced natural language processing, including named entity recognition and tokenization.
    - `Yake`: For unsupervised keyword extraction from single documents.
    - `Rake`: Rapid Automatic Keyword Extraction algorithm for keyword detection.
    - `TextBlob`: Simplified text processing for keyword and sentiment analysis.
    - `KeyBERT`: Used for leveraging BERT embeddings to extract the most relevant keywords from text.
  
* **Graph Creation and Manipulation**:
    - `NetworkX`: A library for the creation, analysis, and manipulation of complex networks (graphs) to model relationships between keywords.

* **Similarity Measurement & Natural Language Processing**:
    - `NLTK (Natural Language Toolkit)`: For tokenizing, parsing, and processing text. Useful in text similarity and linguistic tasks.
    - `textdistance`: For computing different similarity or distance metrics between sequences, such as strings.
  
* **Document Retrieval**:
    - `Wikipedia API`: Used to retrieve relevant articles and documents dynamically from Wikipedia for context expansion.

* **Visualization**:
    - `matplotlib` and `pyplot`: For plotting and visualizing graphs that represent keyword relations and similarity.

### 📈 Graph Algorithms
To determine the most relevant information based on keyword extraction and comparison, several **graph-based algorithms** are employed:

* **Normalized Levenshtein Distance**:
    - Measures the minimum number of single-character edits required to change one word into another.

* **Wu Palmer Similarity**:
    - A semantic similarity metric that calculates the depth of the two words in the taxonomy and the depth of their least common ancestor.

* **Path Similarity**:
    - Calculates the similarity between two words based on the shortest path between them in a semantic hierarchy like WordNet.

* **Jaro-Winkler Similarity**:
    - A string metric measuring the similarity between two strings, adjusting for common prefixes.

This diverse combination of tools, libraries, and algorithms ensures accurate keyword extraction, similarity measurement, and data visualization.

