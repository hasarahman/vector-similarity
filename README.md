# Vector Similarity
This notebook guides you through using Neon Serverless Postgres as a vector database for OpenAI embeddings. It demonstrates how to:

1. Use embeddings created by OpenAI API.
   
2. Store embeddings in a Neon Serverless Postgres database.
   
3. Convert a raw text query to an embedding with OpenAI API.
   
4. Use Neon with the pgvector extension to perform vector similarity search.

I chose Neon because Neon it supports the pgvector open-source extension, which enables Postgres as a vector database for storing and querying vector embeddings. You'll see in the notebook that I've created a sql table to organize my embeddings.

Some issues I ran into:

1. Formatting. Ensuring that you have the appropriate schema for your data.
