# 🎬 Hybrid Recommendation System

## 📌 Project Overview

This project implements a **Hybrid Recommendation System** combining:

* Collaborative Filtering (User-Item similarity)
* Content-Based Filtering (Item features)

The system recommends top-N items based on a weighted hybrid approach.

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---

## 📂 Dataset

* MovieLens 100K dataset
* Contains user ratings and item metadata

---

## 🚀 How It Works

1. Load dataset
2. Create user-item matrix
3. Compute:

   * Collaborative similarity (cosine similarity)
   * Content similarity
4. Combine both using hybrid formula
5. Generate top recommendations

---

## ▶️ How to Run

### Step 1: Install dependencies

```bash
pip install pandas numpy scikit-learn
```

### Step 2: Run notebook

Open:

```
recommendation.ipynb
```

Run all cells.

---

## 📊 Example Output

```
[('Aladdin (1992)', 0.724),
 ('Willy Wonka and the Chocolate Factory (1971)', 0.652),
 ('Beavis and Butt-head Do America (1996)', 0.624)]
```

---

## 📌 Author

Hriday Dewan
