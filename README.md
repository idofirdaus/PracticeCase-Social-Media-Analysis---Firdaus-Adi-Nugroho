# PracticeCase-Social-Media-Analysis
by Firdaus Adi Nugroho

--------------------------------------------------------
## Practice Case ini menggunakan:
### Dataset: Dataset Twitter
    - Kolom: 2 (Tweet dan target)
    - Baris: 1,6 Juta rows
    
### Objectives:
    - Melakukan sentimen analisis dari dataset twitter
    - Melakukan modelling mana yang terbaik untuk  sentimen analisis
    
    
### Steps:
   1. Overview: Melakukan Awalan pengelolaan Data dari load data hingga melihat informasi-informasi menyeluruh data.
   2. Data Cleansing: Terdapat missing value dalam data ini, sehingga perlu ada aksi yg dilakukan. Karena missing valuenya hanya sedikit, maka hanya perlu dihapus saja missing valuenya
   3. Data Pre-Processing: Pada proses ini, pengelolaan text agar optimal. Contohnya melakukan seperti Lower Case Text, Punctional Removal, Stopwords, Frequent Word Removal, dan lain lain
   4. Data Visualization: Visualisasi dilakukan agar melihat persebaran data sentimen dari menggunakan Pie-Chart, dan WordCloud
   5. Feature Extraction: Feature Extraction dilakukan agar mendukung proses modelling agar lebih mudah seperti melakukan sampling, Count Vectorizer, dan TF-IDF Vectorizer.
   6. Modelling: Melakukan split data training, dan testing terlebih dahulu, lalu melakukan proses Modelling. Modelling yang dilakukan adalah Naive Bayes, Logistic Regression, Decision Tree, dan Random Forest
   7. Evaluasi: Dari melakukan Modelling tersebut, maka dihasilkan hasil evaluasi mengunakan Recall, Precision dan F1 serta ada juga GAP antara setiap evaluasi dari training dan testing
