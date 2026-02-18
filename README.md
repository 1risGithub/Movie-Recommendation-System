# 🎬 Movie Recommendation System

ระบบแนะนำภาพยนตร์ (Recommendation System) ที่พัฒนาโดยใช้เทคนิค Machine Learning และ Collaborative Filtering เพื่อแนะนำภาพยนตร์ให้ผู้ใช้ตามพฤติกรรมการให้ Rating

โปรเจคนี้ถูกออกแบบเป็น End-to-End Machine Learning Pipeline ตั้งแต่ Data Cleaning จนถึง Deployment

---

# 🎯 Objective

- สร้างระบบแนะนำภาพยนตร์สำหรับผู้ใช้
- ใช้ Collaborative Filtering
- ใช้ Cosine Similarity เพื่อคำนวณความคล้ายกัน
- สามารถ Deploy และใช้งานจริงได้

---

# 🏗 Machine Learning Pipeline

```
DataCleaning.ipynb
↓
Preprocessing.ipynb
↓
Explore.ipynb
↓
Modeling.ipynb
↓
Deployment.ipynb
```

---

# 📂 Project Structure

```
Movie-Recommendation-System/

├── DataCleaning.ipynb
├── Preprocessing.ipynb
├── Explore.ipynb
├── Modeling.ipynb
├── Deployment.ipynb

├── data/
├── models/

├── README.md
└── requirements.txt
```

---

# ⚙ Tech Stack

## Language

Python

## Libraries

- Pandas
- NumPy
- SciPy
- Scikit-learn
- Pickle

## Machine Learning Technique

- Collaborative Filtering
- Cosine Similarity
- Sparse Matrix

---

# 🧹 DataCleaning

ขั้นตอน:

- Remove missing values
- Remove duplicates
- Clean dataset

Output:

Clean dataset ready for preprocessing

---

# ⚙ Preprocessing

ขั้นตอน:

- Transform data
- Create User-Movie Matrix
- Convert to Sparse Matrix

โครงสร้าง:

```
Users × Movies Matrix
```

เพื่อเพิ่ม performance และลด memory usage

---

# 📊 Explore (EDA)

วิเคราะห์ข้อมูล เช่น:

- จำนวน users
- จำนวน movies
- จำนวน ratings
- Distribution ของ ratings

เพื่อเข้าใจ dataset ก่อน train model

---

# 🤖 Modeling

ใช้:

Collaborative Filtering

และ

Cosine Similarity

ตัวอย่าง:

```python
cosine_similarity(user_matrix)
```

สร้าง recommendation function

```python
recommend_movies(user_id)
```

---

# 💾 Deployment

สามารถ:

- Save model
- Load model
- Run recommendation

ตัวอย่าง:

```python
load_model()

recommend_movies(user_id=1)
```

---

# 🚀 Example Output

```
Recommended Movies:

Movie 1
Movie 2
Movie 3
Movie 4
Movie 5
```

---

# 🎯 Applications

สามารถนำไปใช้กับ:

- Movie Recommendation
- Product Recommendation
- Music Recommendation
- E-commerce Recommendation

---

# 📈 Future Improvements

- Deep Learning Recommendation
- Hybrid Recommendation System
- Web Application
- API Deployment

---

# 👨‍💻 Author

Latte

Machine Learning / AI Developer

---

# 📜 License

MIT License
