# decodelabs-_tasks_MariamAllam
# Artificial Intelligence Internship projects

Welcome to my AI portfolio. I am a third-year Computer Science student and certified Data Analytics graduate, currently building production-ready architectures. 

This repository contains my projects from the DecodeLabs Industrial Training program. The focus of this repository is on bridging theoretical machine learning concepts with practical, scalable programmatic execution—transitioning from deterministic control flows to mathematical vector mappings.

---

## 📂 Project 1: Rule-Based Logic Engine (AI Chatbot)
**Directory:** `Task_1_MariamAllam/`

Most beginner rule-based bots rely on structurally weak `if-elif` ladders with linear time complexity. This project abandons that anti-pattern in favor of an industrial-grade Logic Engine. It operates on a strict Input-Process-Output (IPO) model, relying purely on deterministic programmatic decision-making.

**Core Features:**
* **Instantaneous Lookup:** Replaced sequential scanning with Hash Maps (Python Dictionaries) to achieve an `O(1)` constant time complexity, allowing the knowledge base to scale limitlessly without performance degradation.
* **Input Sanitization:** Engineered a noise-reduction pipeline using Regular Expressions (`re`) to normalize raw user input, stripping whitespace and punctuation before intent matching.
* **Dynamic Dataset Integration:** Designed to ingest external open-source `intents.json` files, seamlessly mapping complex structured data into the `O(1)` engine.
* **Contextual Memory:** Features basic state-tracking to handle conversational context and synonym mapping for intent aliases.

---

## 📂 Project 2: Tech Stack Matchmaker (Content-Based Recommender)
**Directory:** `Task_3_MariamAllam/`

A content-based filtering system designed to cure "Choice Overload." Instead of relying on collaborative community behavior, this engine utilizes raw item attributes to map user skills directly to specific job roles (e.g., matching "Python, SQL, Machine Learning" to "Data Scientist"). 

**Core Features:**
* **TF-IDF Vectorization:** Solved the limitation of binary overlap by utilizing Term Frequency-Inverse Document Frequency. This mathematical weighting accurately penalizes generic tech terms (like "code") and rewards highly specific skills.
* **Cosine Similarity Engine:** Evaluated multidimensional arrays using Cosine Similarity rather than Euclidean distance, ensuring the algorithmic matching is strictly based on the angular alignment of interests, invariant to the magnitude of the job description.
* **The 4-Step Ranking Pipeline:** 
  1. **Ingestion:** Captures explicit user profiles (minimum data density enforced to bypass User Cold Starts).
  2. **Scoring:** Transforms strings to a shared vocabulary space and computes the similarity dot product.
  3. **Sorting:** Organizes the matrix elements in descending order.
  4. **Filtering:** Truncates the output into a precise "Top-N" list.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Data Manipulation:** Pandas, JSON
* **Machine Learning & Math:** Scikit-learn (`TfidfVectorizer`, `cosine_similarity`)
* **Text Processing:** Python `re` (Regular Expressions)
* **Environment:** Jupyter Notebook / Google Colab

---
