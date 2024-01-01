# PDF-Reader-LLM
Creating a LLM based Generative Model which can be trained with a given custom PDF and answer questions using it.

- The Model here used is Meta-AI's Llama - 7B Model, in a quantised version developed by TheBloke and is available on HuggingFace and can be accessed [here](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML)

- The PDF Used here is the budget allocation PDF for year 2023, the answers by the models are found to be accurate.

- Here, a point to note is that the text is extracted from PDF and converted into Vector Embeddings in order to better perform Similarity Search for identifying relevant texts associated with the questions and hence answering the question accurately.

- This Use case is very useful for the work which involves going through multiple documents and generating insights and deriving conclusions from them.
