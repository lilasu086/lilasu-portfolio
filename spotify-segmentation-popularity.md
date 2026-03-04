# 🎧 Spotify Listener Segmentation & Popularity Analysis

## 📌 Business Problem
Music streaming platforms like Spotify generate vast amounts of data on user listening habits and track popularity. Yet, understanding **which listener segments and audio features drive popularity** is challenging. This project aims to decode what makes certain tracks popular and how listener behaviors vary across segments, enabling more informed decision-making for music marketing and content strategy.

---

## 🎯 Objective
Segment Spotify listeners based on listening patterns and explore relationships between audio features and track popularity to uncover data-driven insights on what drives popularity in music.

---

## 📍 Data & Approach

### 📊 Data
- Spotify track metadata and listener behavior records
- Audio features: danceability, energy, acousticness, tempo, etc.
- Popularity scores representing listener engagement

### 🛠 Methodology
1. **Data Preprocessing**
   - Cleaned audio metadata and handled missing values
   - Normalized numerical features for analysis

2. **Segmentation**
   - Clustered listeners using behavioral and audio attributes
   - Identified listener groups with similar listening patterns

3. **Popularity Analysis**
   - Explored correlations between song attributes and popularity
   - Visualized feature distributions by popularity tiers

4. **Insights Extraction**
   - Examined key features that distinguish highly popular songs
   - Interpreted listener segment differences to inform strategy

---

## 📈 Key Insights

- **Popularity Attributes:** No single audio feature dominates, but combinations of features like energy and danceability are meaningful in defining listener appeal. :contentReference[oaicite:0]{index=0}  
- **Listener Clusters:** Distinct user groups show different preferences — some prefer high-energy tracks while others favor acoustic or mellow styles.  
- **Popularity Patterns:** Popular songs tend to balance multiple audio characteristics rather than excel in only one.

---

## 💡 Business Recommendation

✔ **Music Marketing Optimization:** Focus promotional efforts on tracks that score high across combined audio traits associated with broader appeal.  

✔ **Audience-Driven Curation:** Tailor playlists to specific listener segments (e.g., high-energy preference vs. mellow listeners) to maximize retention and engagement.

✔ **Predictive Feature Use:** Use identified audio patterns to inform A&R and content strategy — adapt releases based on feature profiles that align with popular segments.

---

## 🧰 Tools & Techniques
- Python, Pandas, Scikit-Learn  
- Clustering & Segmentation  
- EDA and Visualization

---

🔗 **Full Notebook & Code:**  
https://github.com/lilasu086/Spotify-Listener-Segmentation-Popularity-Analysis
