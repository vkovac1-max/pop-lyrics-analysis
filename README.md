# From Poetry to Production: Lyrical Simplification in Pop Music (1959-2023) 🎵📊

## About the Project
This project explores the evolution of popular music over six decades using Data Science. By analyzing the lyrics and metadata of Billboard Top 100 hits from 1959 to 2023, this study tests two main hypotheses:

1. **The "Industrialization" of Authorship:** Has the average number of writers per song systematically increased?
2. **Lyrical Simplification:** Has the lexical complexity (measured via TTR) of mainstream music declined over time?

*Note: This project was completed as part of the "Introduction to Data Science" course at Juraj Dobrila University of Pula.*

## Key Findings 📈
* **The Death of the Solo Writer:** Data shows a dramatic spike in the average number of writers per song starting in the 1990s. Modern hits have shifted from single lyricists to collaborative production models.
* **Decline in Lexical Diversity:** Using the **Type-Token Ratio (TTR)** to measure vocabulary richness, the analysis reveals a historical decline. Modern songs tend to have more words in total, but those words are significantly more repetitive.
* **Case Study:** A direct comparison between Queen's *Bohemian Rhapsody* (TTR: 0.421, 1 writer) and Taylor Swift's *Shake It Off* (TTR: 0.191, 3 writers) highlights this 60-year shift.

## Tech Stack 🛠️
* **Language:** Python
* **Data Manipulation:** Pandas
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 📂 Dataset
The raw dataset used for this project exceeds GitHub storage limits (29 MB). You can download the original data here: 
**[Top 100 Songs and Lyrics (1959-2019) on Kaggle](https://www.kaggle.com/datasets/brianblakely/top-100-songs-and-lyrics-from-1959-to-2019)**

## How to View 🚀

### 1. Quick View (Recommended)
* **Open the `.html` file** – Download and open this file in your browser. This is the best way to see the full report, all graphs, and the analysis beautifully formatted without any page breaks.

### 2. Interactive Code (Jupyter)
If you want to run the code yourself:
1. **Download the `.ipynb` file** from this repository.
2. **Download the dataset** from the [Kaggle link](https://www.kaggle.com/datasets/brianblakely/top-100-songs-and-lyrics-from-1959-to-2019) provided above.
3. Place both the `.ipynb` file and the `.csv` file in the **same folder** on your computer.
4. Run it using Jupyter Notebook or VS Code.
