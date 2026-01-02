Install LanceDB and Pandas via pip

!pip install lancedb --quiet
!pip install pandas --quiet

Then restart Kernel


Features Overview

The program demonstrates the creation of synthetic real estate listings, their storage in a vector database (LanceDB), and a semantic search functionality that delivers personalized results based on buyer preferences. Using a Large Language Model (LLM), 10 realistic and diverse real estate listings are generated, including details such as name, location, price, size, amenities, and description. These listings are stored in a vector database (LanceDB) by converting them into embeddings, enabling efficient semantic search.

The system accepts buyer preferences such as budget, location, or desired amenities and searches the database for the best-matching listings. The retrieved results are personalized using the LLM by highlighting relevant features without altering factual information. This creates appealing and individually tailored descriptions.

The program includes steps for listing generation, database storage, preference-based search, and description personalization. Buyers can quickly find properties that match their preferences and receive optimized descriptions to simplify their decision-making process.