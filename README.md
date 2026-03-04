# From Poetry to Production: Lyrical Simplification in Pop Music (1959-2023) 🎵📊

## About the Project
This project explores the evolution of popular music over six decades using Data Science and **Quantitative Text Analysis**. By analyzing the lyrics and metadata of Billboard Top 100 hits from 1959 to 2023, this study provides empirical evidence for two major shifts in the music industry:
1. **The "Industrialization" of Authorship:** Investigating the systematic increase in the average number of writers per song.
2. **Lyrical Simplification:** Measuring the mathematical decline of lexical complexity in mainstream hits.

*Note: This project was completed as part of the "Introduction to Data Science" course at Juraj Dobrila University of Pula (UNIPU).*

## Key Findings 📈
* **The Death of the Solo Writer:** The analysis identifies a dramatic spike in production team sizes starting in the 1990s. Modern hits have shifted from single lyricists to highly collaborative, industrialized production models.
* **Decline in Lexical Diversity:** Using the **Type-Token Ratio (TTR)** to measure vocabulary richness, the data reveals a historical downward trend. Modern songs feature higher total word counts but significantly higher rates of textual repetition.
* **Case Study - Queen vs. Taylor Swift:** A direct mathematical comparison between *Bohemian Rhapsody* (TTR: 0.421, 1 writer) and *Shake It Off* (TTR: 0.191, 3 writers) serves as a perfect microcosm of this 60-year evolution.

## Tech Stack & Methodology 🛠️
* **Language:** Python
* **Data Engineering:** Pandas (Complex string manipulation and unique word indexing)
* **Metrics:** Type-Token Ratio (TTR) for quantitative linguistic complexity
* **Data Visualization:** Matplotlib, Seaborn (Time-series trend analysis and distribution plots)
* **Environment:** Jupyter Notebook

## 📂 Dataset Note
The raw dataset used for this project ("Top 100 Songs & Lyrics By Year 1959-2023") exceeds standard GitHub storage limits. 
You can download the original raw data directly from Kaggle: 
**[Top 100 Songs and Lyrics (1959-2019) on Kaggle](https://www.kaggle.com/datasets/brianblakely/top-100-songs-and-lyrics-from-1959-to-2019)**

*To run the notebook locally, place the Kaggle `.csv` file in the same root directory as the `.ipynb` file.*

## How to View
* **🚀 Best Experience:** Download and open the **`Lyrical_Simplification.html`** file in your browser. This provides a continuous, high-resolution view of the full report without the page-break issues of standard PDFs.
* **Code:** View the **`.ipynb`** file directly on GitHub for the source code and implementation details.
