# 🎬 Personalized Movie Recommendation Engine (NLP & Association Rules)

## 📌 Business Problem
Streaming platforms and movie services need to deliver personalized movie recommendations to keep users engaged, reduce churn, and improve satisfaction. Traditional collaborative filtering may miss thematic and semantic patterns in movie content, leading to suboptimal suggestions.

---

## 🎯 Objective
Build a hybrid recommendation system that combines **Natural Language Processing (NLP)** and **association rule mining** to provide personalized movie suggestions based on plot descriptions and user behavior signals.

---

## 📍 Data & Approach

### 📊 Data
- Dataset with 900K+ movies including titles, genres, plot summaries, and metadata  
- User ratings and interaction patterns (where available)

### 🛠 Methodology

1. **Data Preprocessing**
   - Clean text (remove stopwords, punctuation)
   - Tokenize and normalize movie plot summaries  
   - Extract relevant features for content similarity

2. **NLP Feature Extraction**
   - Use **TF-IDF**, **Word2Vec**, and **GloVe** to convert text into numeric vectors  
   - Capture semantic meaning of movie descriptions

3. **Association Rule Mining**
   - Generate rules from user-movie interactions
   - Discover frequent co-occurring movie pairs

4. **Clustering & Recommendation**
   - Apply clustering to group movies with similar story and user patterns
   - Form personalized recommendations using a hybrid of content similarity + association signals

---

## 📈 Key Insights

- **Semantic similarity matters:** NLP embeddings (e.g., Word2Vec) capture plot-level similarity beyond genre tags alone.  
- **Association rules enhance personalization:** Frequent itemsets help recommend movies that users with similar tastes enjoyed together.  
- **Hybrid approach improves relevance:** Combining text semantics with behavior patterns yields higher engagement potential than either method alone.

---

## 💡 Business Recommendation

✔ **Enhanced Recommendation Strategy:** Deploy hybrid recommendation engine to improve relevance and user satisfaction.  
✔ **User Retention:** Platforms can increase session duration and reduce churn by serving more contextually meaningful suggestions.  
✔ **Marketing Integration:** Use clusters and association rule insights to tailor promotional movie categories and email campaigns.

---

## 🧰 Tools & Techniques
- Python (Pandas, Scikit-Learn, NLTK)
- NLP: TF-IDF, Word2Vec, GloVe
- Association Rules (Apriori)
- Clustering methods

---

🔗 **Full Notebook & Code:**  
https://github.com/lilasu086/Personalized-Movie-Recommendation-Engine-NLP-Association-Rules-
