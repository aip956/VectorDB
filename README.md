# Welcome to My Vector DB
***

## Task
TODO - What is the problem? And where is the challenge?

## Description
System to store, manage, and query high-dimensional vectors
General steps:
1. Understand requirements
   1. Data Type
   2. Core Features
      1. Insert vectors; optional metadata
      2. Query vectors based on similarity (e.g. nearest neighbor search)
      3. Update or delete vectors
      4. Support metadata filtering
   3. Performance Goals: Fast queries and scalability (large datasets)
2. Data Ingestion
   1. Initial Prep
      1. Define the format of input data: text, numbers, images, etc.
      2. Decide on the method to convert inputs to vectors (embedding generation)
   2. Embedding Generation
      1. Determine model (OpenAI Embeddings, Hugging Face Transformers, or custom-trained models to generate vectors)
      2. Ensure vectors have a fixed dimension and are normalized if required by similarity metric
   3. Data Storage
      1. Choose a data stucture or storage mechanism
         1. In-Memory Storage: Use Python dictionaries or NumPy arrays for small-scale datasets
         2. Persistent Storage: Use file-based formats (e.g. JSON) or databases (e.g. SQLite, PostgreSQL) to persist vectors
         3. Hybrid Storage: Keep frequently accesses vectors in memory and the rest on disk
   4. Indexing
      1. Brute Force (baseline): Compare the query vector with all stored vectors. Simple, but slow.
      2. Tree-based Structures: KD-Trees or Ball-Trees for low-dimensional data
      3. Approximate Nearest Neighbors (ANN)
         1. Use libraries like FAISS, Annoy, or HNSWlib for large-scale and high-dimensional datasets
         2. Implement techniques like Locality Sensitive Hashing (LSH) for faster lookups
   5. Querying
      1. 

## Installation
TODO - How to install your project? npm install? make? make re?

## Usage
TODO - How does it work?
```
./my_project argument1 argument2
```

### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>
