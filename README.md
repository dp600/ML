# 🧠 Amazon product Review using Clustering Technique(unsupervised learning) and Preprocessed by NLTK

## Objective  
This project aimed to uncover hidden patterns in Amazon product reviews using unsupervised machine learning. By converting review texts into numerical vectors using **TF-IDF**, and applying **KMeans clustering**, the project grouped similar reviews and extracted top keywords per cluster. This enables understanding of major themes or topics customers frequently talk about.

---

### Tasks

1. Preprocessed text using **NLTK**: tokenization, stopword removal, etc.
2. Converted review text into TF-IDF vectors.
3. Applied **KMeans Clustering** to group similar reviews.
4. Extracted and displayed **top keywords for each cluster**.
5. Visualized cluster insights to interpret major review themes.

---

### Skills Learned

1. Text pre-processing (tokenization, cleaning)
2. Vectorizing text with **TF-IDF**
3. Applying **KMeans** for unsupervised learning
4. Evaluating clusters using inertia and the Elbow method
5. Extracting meaningful keywords from clusters
6. Interpreting clustering output for real-world product insights

---

### Tools Used

- **Python (Google Colab / Jupyter Notebook)**
- **Libraries**: `NLTK`, `Scikit-learn`, `Pandas`, `Matplotlib`, `Scipy`,`Seaborn`,`Numpy`
- **NLP Methods**: `TfidfVectorizer`, `KMeans`
- **Evaluation**: Elbow Method (Inertia), Keyword Extraction
- **Visualization**: Bar charts of top terms per cluster
- **AI Rapid Studio**: for evaluation of the process and result
---

## 📈 Output

- **Preprocessed** Seven hundred one thousand five hundred fifty-nine (7015559) of Amazon reviews for meaningful clustering.
- Chose optimal number of clusters (e.g., `k=5`) using the Elbow method.
- Grouped reviews into 5 thematic clusters using KMeans.

<img width="1237" height="1125" alt="image" src="https://github.com/user-attachments/assets/c7b2e364-cc37-4433-a48d-303b0168b2d0" />



<img width="658" height="438" alt="image" src="https://github.com/user-attachments/assets/2e93dbe2-d178-4d08-b543-6b3693dc69d9" />


- **Top Keywords per Cluster** extracted for interpretation:
Clusters 0  These had a review on hair growth and grooming. These were neutral but slightly positive
Clusters 1  These were involved with Oily Hair and Greasiness. This represent negative sentiments
Cluster 2: It presents Product effectiveness and Use. Reviewers' sentiment were more neutral
Cluster 3. User sentiment was neutral. It’s involved in Usability and handling
Cluster 4:  It represents strong Emotional Reactions and brand Affinity. User sentiment was highly positive



<img width="627" height="523" alt="image" src="https://github.com/user-attachments/assets/2460dc2f-5c97-45f9-9611-79a594f0af5a" />
