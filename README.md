# 🍲 Recipe Recommender AI

A smart recipe recommendation system that leverages **Natural Language Processing (NLP)** and **Machine Learning** to suggest recipes based on user preferences and input ingredients. This project aims to help users discover delicious meals that fit their available ingredients, dietary needs, or taste preferences.

---

## 🧠 Project Overview

The goal of this project is to build an AI-powered system that can:

- Recommend the best recipes from a dataset based on ingredient similarity.
- Understand user input using NLP techniques.
- Rank recipes by relevance using cosine similarity and TF-IDF.
- Provide a web interface for users to interact with the model.

---


## 📊 Dataset

The dataset used (`recipes.csv`) includes:

- `Title`: Name of the recipe
- `Ingredients`: List of ingredients used
- `Instructions`: Cooking steps

The data is cleaned and preprocessed to remove duplicates, normalize text, and tokenize ingredients for better matching.

---

## 🔍 Recommendation Logic

1. **Text Preprocessing:**
   - Convert to lowercase
   - Remove stopwords and punctuation
   - Lemmatization for standardizing words

2. **Feature Extraction:**
   - TF-IDF vectorization to capture term importance
   - Cosine similarity to compare user input vs. existing recipes

3. **Matching:**
   - The system returns the top N recipes that best match the user's ingredients.

---

## 💡 Key Features

- ✅ Input ingredient list via a clean web interface
- ✅ Fast and accurate recipe matching using cosine similarity
- ✅ Scalable architecture using Flask for deployment
- ✅ Clean modular code for easy experimentation

---
🧰 Technologies Used
	•	Python 3
	•	Flask (for the web app)
	•	Pandas (data handling)
	•	Scikit-learn (TF-IDF & cosine similarity)
	•	NLTK / SpaCy (text preprocessing)
	•	HTML/CSS (frontend)

⸻

📌 Future Improvements
	•	🔄 Add collaborative filtering or deep learning models (e.g., BERT-based semantic search)
	•	📱 Build a mobile version
	•	🌐 Deploy to a cloud service (Heroku, Render, etc.)
	•	🧠 Add personalization using user history and dietary filters

⸻

🤝 Contributions

Have a recipe idea or want to improve the algorithm? Contributions are welcome!
	•	Fork the repository
	•	Create a new branch
	•	Make changes and submit a pull request

⸻

📧 Contact

Made with ❤️ by Chaitanya Handore
📫 Email: chaitanyahandore@gmail.com
🔗 LinkedIn | GitHub


