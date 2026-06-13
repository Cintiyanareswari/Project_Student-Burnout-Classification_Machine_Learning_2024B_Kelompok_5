# Analisis Pengaruh Tekanan Akademik terhadap Risiko Burnout Mahasiswa Menggunakan Algoritma Support Vector Machine dan Random Forest

## Deskripsi Proyek

Proyek ini merupakan tugas akhir mata kuliah Pembelajaran Mesin Dasar Program Studi Sains Data Universitas Negeri Surabaya Semester Genap 2025/2026.

Penelitian bertujuan untuk mengklasifikasikan tingkat risiko burnout mahasiswa (Low, Medium, High) berdasarkan faktor akademik, psikologis, dan gaya hidup menggunakan algoritma Support Vector Machine (SVM) dan Random Forest.

---

## Anggota Kelompok

1. Putri Sofiyatus Salwa (24031554112)
2. Adisti Eka Nabila (24031554119)
3. Cintiya Agustin Nareswari (24031554218)

Kelas: Sains Data 2024B

---

## Dataset

Dataset yang digunakan:

Student Mental Health and Burnout Dataset

Source:
https://www.kaggle.com/datasets/sharmajicoder/student-mental-health-and-burnout

Jumlah data awal: 1.000.000 baris

Jumlah data setelah sampling: 500.000 baris

---

## Metodologi

Tahapan penelitian:

1. Data Collection
2. Data Understanding
3. Exploratory Data Analysis (EDA)
4. Sampling
5. Leakage Analysis
6. Preprocessing
7. Train-Test Split
8. Data Transformation
9. SMOTE
10. Model Development
11. Hyperparameter Tuning
12. Evaluation
13. Feature Importance Analysis
14. Model Comparison

---

## Algoritma

### Support Vector Machine (SVM)

Parameter baseline:

- C = 1
- loss = squared_hinge
- max_iter = 2000

Parameter terbaik:

- C = 0.1
- loss = squared_hinge
- max_iter = 3000

### Random Forest

Parameter baseline:

- n_estimators = 100
- max_depth = 20
- min_samples_leaf = 2

Parameter terbaik:

- n_estimators = 200
- max_depth = 30
- min_samples_split = 5
- min_samples_leaf = 2
- max_features = log2

---

## Hasil

| Model | Accuracy | F1 Macro |
|---------|---------|---------|
| SVM Baseline | 0.81865 | 0.58453 |
| SVM Tuned | 0.81866 | 0.58454 |
| RF Baseline | 0.83027 | 0.67461 |
| RF Tuned | 0.83837 | 0.68487 |

Model terbaik: Random Forest Tuned

---

## Feature Importance

Fitur yang paling berpengaruh:

- Stress Level
- Anxiety Score
- Depression Score
- Sleep Hours
- Exam Pressure
- Social Support

---

## Tools

- Python
- Pandas
- NumPy
- Scikit-Learn
- Imbalanced-Learn
- Matplotlib
- Seaborn

---

## Repository

Project Machine Learning Dasar
Program Studi Sains Data
Universitas Negeri Surabaya
