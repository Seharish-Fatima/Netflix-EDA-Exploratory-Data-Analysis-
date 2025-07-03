# 🎬✨ Netflix EDA: Unmasking the Streaming Empire ✨📊

> **Project Motto:** _"We don’t just stream shows — we stream insights."_  
> Buckle up, because we’re about to serve data analysis hotter than a season finale cliffhanger. This project dives deep into Netflix’s catalogue to uncover what makes it tick, click, and stick. 📈🍿

---

## 📦 Dataset Details

We used the **Netflix Titles Dataset** — a delicious compilation of metadata for TV Shows and Movies available on Netflix, featuring:

- Title  
- Type (Movie or TV Show)  
- Cast & Crew  
- Country of origin  
- Date added to Netflix  
- Release Year  
- Duration  
- Genres (aka `listed_in`)  
- Description  
...and more streaming goodness.

Imported like:
```python
df = pd.read_csv('netflix_titles.csv')
