
### RAG  Notebook: Shows the output for the treatment and causes of the detected disease
- Load the Crop disease management and treatment information pdfs from the directory and create chunks of them.
- Chunks are converted into embbedings using SENTENCE-BERT Model. ( We can use Gemma model of embeddings also intsead)
- Embeddings are Stored in Index.
- Semantic Search is Carried with respective to query defined for Context Retrival.
- LLM GEMMA 4B generates Context-Aware Answers accordingly to the context and prompt.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ODZAAp9d_9-2mnsMZkVZMBwfihKWLdPH?usp=sharing)
