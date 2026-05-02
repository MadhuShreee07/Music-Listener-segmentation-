# 🎧 Music Listener Segmentation using Streaming Patterns

## 📌 Overview

This project focuses on analyzing music streaming data to understand user listening behavior and segment users into meaningful groups. By leveraging **time-based analysis and clustering techniques**, we identify distinct listener personas that can help improve recommendation systems and user engagement.

---

## 🎯 Objectives

* Analyze music streaming patterns
* Perform **time-based behavioral analysis**
* Segment users using **machine learning (K-Means)**
* Visualize clusters using **PCA**
* Generate insights for personalization and business use

---

## 📊 Dataset Features

The dataset contains detailed streaming behavior including:

* User ID
* Track name & artist
* Timestamp (when the song was played)
* Duration of listening
* Skip behavior (skipped or not)
* Platform used

### 🔧 Derived Features

* Listening frequency
* Average listening duration
* Skip rate
* Time segments (Morning, Afternoon, Evening, Night)

---

## ⚙️ Data Preprocessing

* Handled missing values using **median imputation**
* Converted timestamps into datetime format
* Extracted **hour-based features**
* Performed data validation and consistency checks

---

## ⏰ Time-Based Analysis

The day was divided into 4 segments:

* 🌅 Morning (6 AM – 12 PM)
* ☀️ Afternoon (12 PM – 5 PM)
* 🌇 Evening (5 PM – 9 PM)
* 🌙 Night (9 PM – 6 AM)

This helped identify **peak listening patterns** and user habits.

---

## 🤖 Machine Learning Approach

### 🔹 K-Means Clustering

* Used to group users into clusters based on behavior
* Optimal clusters chosen using **Elbow Method**
* Features were normalized using **StandardScaler**

### 🔹 PCA (Principal Component Analysis)

* Reduced dimensions for visualization
* Helped plot clusters in 2D space
* Retained ~85% variance

---

## 👥 Results: Listener Personas

The model identified **4 key listener types**:

1. 🎧 Heavy Engagers

   * High listening frequency
   * Low skip rate

2. 🎶 Casual Listeners

   * Moderate usage
   * No specific pattern

3. ⏭️ High-Skip Users

   * Frequently skip songs
   * Low engagement

4. 🌙 Night Owls

   * Active mostly at night
   * Unique listening habits

---

## 📈 Key Insights

* Time-based behavior plays a crucial role in understanding users
* Clustering helps identify clear user segments
* Insights can improve:

  * Recommendation systems
  * User retention
  * Targeted marketing

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 🙌 Contributors

* Madhu Shree
* Sanjana


