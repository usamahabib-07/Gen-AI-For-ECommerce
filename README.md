# Gen-AI-For-ECommerce

This project demonstrates the application of Generative AI and data analysis techniques on an Amazon Sales dataset.

## 📂 Project Structure

- **Gen_AI_for_E_Commerce.ipynb**: Main Jupyter notebook containing the following stages:
  
  1. **Fuzzy Logic and Monte Carlo Simulations**  
     Uses `skfuzzy` to model uncertainty and simulate business decision-making using fuzzy rules. Monte Carlo methods support probabilistic evaluation.
  
  2. **Risk Calculation with Fuzzy Logic**  
     Applies fuzzy outputs to derive risk scores for different scenarios or product behaviors.

  3. **Retrieval-Augmented Generation (RAG)**  
     Implements LangChain with Hugging Face embeddings to build a RAG system. It enables querying document chunks using semantic similarity (FAISS vector store).

  4. **Fine-Tuning a Language Model**  
     Fine-tunes a Hugging Face transformer model on e-commerce data to enhance generation quality for downstream tasks like summarization or Q&A.

## ▶️ How to Run

1. **Install requirements:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Open and run the notebook:**
   - You can run the `.ipynb` file using Jupyter Notebook or Jupyter Lab.
   - Make sure all cells are run in sequence.

3. **Expected Libraries:**
   - PyTorch, Torch-XLA
   - LangChain
   - Transformers
   - Matplotlib, Seaborn
   - Pandas, NumPy
   - scikit-learn, scikit-fuzzy
   - TQDM
   - datasets

## 💡 Notes

- The code includes Colab-specific logic; paths may need to be adjusted for local execution.
- GPU acceleration is recommended for transformer-based tasks (RAG & Fine-Tuning).

