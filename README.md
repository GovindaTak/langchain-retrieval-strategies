# 🔍 Retrieval Strategies in LangChain

This project is a hands-on implementation of **various retrieval techniques in LangChain**, showcasing how different strategies like **Similarity Search**, **MMR**, **Self-Query Retriever**, and **Multi-Query Retriever** can be applied to improve the performance of LLM-based applications.

---

## 🎯 Objective

To explore and compare multiple retrieval strategies in the LangChain framework and evaluate their effectiveness in building context-rich responses for Retrieval-Augmented Generation (RAG).

---

## 📦 Technologies & Tools Used

- **LangChain**
- **OpenAI (GPT-3.5 / GPT-4)**
- **FAISS (Vector Store)**
- **Python**
- **Jupyter Notebook / Colab**

---

## 🔧 Implemented Retrieval Strategies

| Strategy              | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| 🔹 Similarity Search   | Basic retrieval based on vector similarity (e.g., cosine distance).         |
| 🔹 Max Marginal Relevance (MMR) | Balances relevance with diversity to avoid redundancy in retrieved chunks. |
| 🔹 Self-Query Retriever | Allows the model to generate its own retrieval queries based on metadata.   |
| 🔹 Multi-Query Retriever | Generates multiple search queries for a single user question to widen context coverage. |

---

## 🧠 What I Learned

✅ Working with LangChain’s retriever classes  
✅ How vector databases like FAISS are used for chunk retrieval  
✅ The impact of retrieval strategy on LLM answer quality  
✅ Improving RAG pipelines with diverse retrieval techniques  
✅ Query transformation and multi-query search  
✅ Metadata indexing and filtering using self-query retrievers  
✅ Modular code structuring for retriever benchmarking


---

## 🚀 How to Run

1. Clone the repository  
 
   git clone https://github.com/GovindaTak/langchain-retrieval-strategies.git
   cd langchain-retrieval-strategies


2. Install dependencies

  

3. Add your OpenAI API key

   ```python
   import os
   os.environ["OPENAI_API_KEY"] = "your-key-here"
   ```

4. Run the notebooks 

---

## 🔍 Sample Use Case

**Query:** "What is the approval process for research grant?"
**Retrieval Comparison:**

* **Similarity Search** → Returns close matches but might miss diversity
* **MMR** → Balances between close matches and coverage
* **Self-Query** → Retrieves relevant documents by intelligently rewriting query
* **Multi-Query** → Covers multiple interpretations of the same question

---

## 🧑‍💻 Author

**Govinda Tak**
🔗 [GitHub Profile](https://github.com/Govinda-Tak)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

