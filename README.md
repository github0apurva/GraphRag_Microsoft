# GraphRag_Microsoft

Using LLM & embeddings from Groq.
# To initialize the process
python -m graphrag.index --init --root ./Data_input
# Indexing execution 
python -m graphrag.index --root ./Data_input
# query execution
python -m graphrag.query \
--root ./Data_input \
--method glocal \
"what is the main theme of the book?"

