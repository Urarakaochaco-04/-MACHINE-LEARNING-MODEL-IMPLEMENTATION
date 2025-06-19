#  MACHINE LEARNING MODEL IMPLEMENTATION

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : BHAVYA SRI DINDUKURTHI

*INTERN ID* : CT04DN375

*DOMAIN* : PYTHON PROGRAMMING

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

### 🎬 **Project Overview: Movie Recommendation System**

**Overview (One Line):**
This project builds a **content-based movie recommendation system** that suggests similar movies based on textual features like genre, keywords, cast, and director using **natural language processing (NLP)** and **cosine similarity**.

---

### 📘 **Project Description (Student-Friendly)**

In this project, we’ve created a smart recommendation system that helps users discover movies similar to the ones they already like. For example, if someone enjoys *Avatar*, this system can recommend other action-packed or visually stunning films like *Independence Day* or *Titan A.E.* without relying on user ratings or external data. Instead, it purely analyzes the **content of the movie** — its description, genre, actors, and director — to find similarities.

The logic is simple: just like how we find similar books based on themes or characters, here we use **text data** from movies to make connections. We begin by collecting and cleaning two datasets: one for movie details (`tmdb_5000_movies.csv`) and one for crew and cast (`tmdb_5000_credits.csv`). These datasets are merged and key columns like `overview`, `genres`, `keywords`, `cast`, and `crew` are extracted.

Each of these fields contains useful words that describe a movie. We clean and combine them into one feature called `tags`. This is where **Natural Language Processing (NLP)** kicks in — using a **CountVectorizer**, we convert this text into numerical values (vectors). Then we calculate the **cosine similarity** between these vectors to find which movies are most alike.

When a user types in a movie name, our `recommend()` function finds the top 5 similar movies based on those vectors.

---

### 🧰 **Tools & Technologies Used**

| Tool                                                      | Purpose                                                  |
| --------------------------------------------------------- | -------------------------------------------------------- |
| **Python**                                                | Main programming language                                |
| **Pandas**                                                | For reading and processing CSV data                      |
| **NumPy**                                                 | Numerical operations                                     |
| **Scikit-learn** (`CountVectorizer`, `cosine_similarity`) | NLP and similarity calculation                           |
| **AST**                                                   | To safely convert stringified Python objects (like JSON) |
| **Jupyter Notebook / VS Code**                            | For writing and running the code                         |

---

### 🧠 **Key Concepts Used**

* **Content-based filtering**: Recommends movies by analyzing features (not user behavior).
* **Feature engineering**: Merging multiple text-based fields into a single tag.
* **NLP with CountVectorizer**: Turns text into vectors that can be compared.
* **Cosine similarity**: Measures how similar two vectors (i.e., movies) are.
* **Data cleaning and transformation**: Ensures the text is usable for analysis.

---

### 📌 Final Thoughts

This is a great example of how **data science and machine learning** can be used in everyday platforms like Netflix or Hotstar. It teaches not only how to build a recommendation system but also how to work with messy data, apply text-processing techniques, and design a real-world product.

*OUTPUT*

![Image](https://github.com/user-attachments/assets/6cecd15e-bf6e-4ef2-8b89-d4bf2587f593)


