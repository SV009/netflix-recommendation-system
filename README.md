🎬 Netflix Content-Based Movie Recommendation System

A personalized recommendation system built using NLP techniques (TF-IDF and Cosine Similarity) to suggest similar movies and TV shows from Netflix's catalog based on user input. Designed to enhance user experience through relevant and diverse content discovery.

---

🚀 Project Overview

With 8,800+ titles on Netflix, users often face decision fatigue. This system helps them find similar content by analyzing descriptions, genres, cast, and other metadata. The engine uses content-based filtering — no user history required.

---

🧠 Key Techniques
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Cosine Similarity
- Content-Based Filtering
- Evaluation: Genre Overlap, Novelty, Diversity, Catalog Coverage

---

📁 Repository Structure


---

🛠️ How It Works

1. Data Preprocessing: Cleaned and combined text-based metadata
2. TF-IDF Vectorization: Converted metadata into numerical format
3. Cosine Similarity: Computed similarity between movies
4. Top-N Recommendations: Returned most similar titles for input

---

📈 Evaluation (on 103 test cases)

| Metric                | Result     |
|-----------------------|------------|
| 🎯 Genre Overlap      | 21.4%      |
| 🔁 Diversity (ILS)    | 0.093      |
| 🌟 Novelty            | 88.96%     |
| 📚 Catalog Coverage   | 9.98%      |

---

📸 Sample Output

**Input**: `Chappie` (Sci-Fi/Action)  
**Recommendations**: District 9, Real Steel, AlphaGo, Hardcore Henry

**Input**: `Blood & Water` (Teen Drama)  
**Recommendations**: Kings of Jo'Burg, Diamond City, Shirkers

---

📎 Reports

- 📄 [Milestone 1]
- 📄 [Milestone 2]
- 📄 [Final Report]
- 📊 [Presentation Slides]

---


