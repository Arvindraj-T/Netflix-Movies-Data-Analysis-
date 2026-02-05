
   Most frequent genres on Netflix visualized using `sns.catplot()`

2. **Vote Average Distribution**  
   Categorized vote averages plotted to show viewer sentiment

3. **Popularity Extremes**  
   - Highest popularity movie and its genre
   - Lowest popularity movie and its genre

4. **Release Year Trends**  
   Histogram showing which years had the most movie releases

---

## 🔍 Key Insights

- 🎬 **Most Frequent Genre:** Identified using value counts and visualized
- ⭐ **Vote Analysis:** Categorized viewer ratings into meaningful buckets
- 🔥 **Top Movie by Popularity:** Extracted using `df['Popularity'].max()`
- 🧊 **Least Popular Movie:** Extracted using `df['Popularity'].min()`
- 📅 **Peak Release Year:** Visualized with histogram

---

## 📂 Folder Structure
```
Netflix-Movies-Analysis/
├── mymoviedb.csv 
├── NetflixDataAnalysis.py
├── README.md
├── outputs/
           │ ├── genre_distribution.png
           │ ├── vote_distribution.png 
           │ └── release_year_histogram.png
 ```
## 📊 Sample Visualizations

### 🎬 Genre Distribution
![Genre Distribution](genre_distribution.png)

### ⭐ Vote Average Distribution
![Vote Distribution](vote_distribution.png)

### 📅 Release Year Histogram
![Release Year Histogram](release_year_histogram.png)








           
