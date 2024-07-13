# StepsAssignment
Project Description: Implementation of Web Scraping and Advanced Retrieval Augmented Generation

The project repository comprises 4 IPython notebooks focusing on distinct functionalities:

  Scraping: This notebook effectively scrapes data from a specified link. It not only retrieves data from the primary link but also extracts information from       
            subsequent sub-links up to a depth of 5 levels.

  Chunking: Utilizing the langchain framework, this notebook segments the large volume of scraped data into smaller text chunks. This approach is essential due to 
            the contextual limitations of Large Language Models (LLMs).

  Embeddings: This notebook employs the "sentence-transformers/all-MiniLM-L6-v2" model to generate embeddings for the text chunks created earlier. These embeddings, 
             along with their corresponding text chunks and URLs, are stored in a vector database.

  Retrieval: Focused on advanced techniques in Retrieval Augmented Generation(RAG), this notebook enhances system performance through sophisticated retrieval methods.

Each notebook within the repository serves a crucial role in facilitating comprehensive data retrieval, processing, and enhancement using advanced techniques.
