# 🎬 Netflix Movies Data Analysis (Python)

## 📌 Overview
This project analyzes a dataset of **9,800+ Netflix movies and TV shows** to uncover insights into genres, popularity, ratings, and release trends. Using **Python, Pandas, Matplotlib, and Seaborn**, the workflow demonstrates how to clean, transform, and visualize large datasets for meaningful insights.

---

## 🛠️ Tech Stack
- **Python**  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

## 📂 Dataset
- **Rows:** 9,827 (expanded to 25,552 after genre splitting)  
- **Columns:** Release Date, Title, Popularity, Vote Count, Vote Average, Genre  
- **Cleaning Steps:**
  - Converted release dates to year format  
  - Removed duplicates and unnecessary columns  
  - Categorized vote averages into: *popular, average, below average, not popular*  
  - Exploded multi-genre entries into individual rows  

---

## 📊 Analysis & Visualizations
- **Genre Distribution:** Drama is the most frequent genre (~14%)  
- **Votes:** 25.5% of movies categorized as *popular*  
- **Popularity:**  
  - Highest → *Spider-Man: No Way Home* (Action, Adventure, Sci-Fi)  
  - Lowest → *The United States vs. Billie Holiday* & *Threads (1984)*  
- **Release Trends:** Year 2020 recorded the highest number of releases  

---

## 📈 Key Insights
- Drama dominates Netflix’s catalog  
- Spider-Man: No Way Home is the most popular movie  
- 2020 had the peak in movie releases  
- Categorization of ratings provides clearer audience preference analysis  

---

## 🚀 How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/netflix-movies-analysis.git

