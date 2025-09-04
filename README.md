## Open this project in your browser

| Notebook        | Colab |
|-----------------|-------|
| `scraper_zm.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AHMerrill/Unstructured-Data-1/blob/main/scraper_zm.ipynb) | 
| `vectorizer_lift_MDS_zm.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AHMerrill/Unstructured-Data-1/blob/main/vectorizer_lift_MDS_zm.ipynb) |
| `zipf_zm.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AHMerrill/Unstructured-Data-1/blob/main/zipf_zm.ipynb) | 

## In colab, if you make changes to notebooks, use "save in github" at the top of the page to re-commit.
## Download any created csv or other files and re-commit those manually.


| Task                           | What                                                                                                                             | File/Notebook | Done by | Date | Validated by | Notes / PR |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------- | ---- | ------------ | ---------- |
| **Scraper implemented**        | Python scraper; handles forum HTML & threading; drops block quotes                                                               |               |         |      |              |            |
| **Scrape 8–10k posts**         | CSV with `userid,date,message` columns produced                                                                                  |               |         |      |              |            |
| **Toy data check**             | Tiny CSV + hand-calculated lift compared to code                                                                                 |               |         |      |              |            |
| **Task A: Zipf test**          | OLS regression on log–log; slope test; plot top-100 words vs theory                                                              |               |         |      |              |            |
| **Task B: Top-10 brands**      | Stopwords removed; models collapsed into brands; 1 mention/msg                                                                   |               |         |      |              |            |
| **Task C: Lift (top-10 only)** | Lift table for top-10 brands                                                                                                     |               |         |      |              |            |
| **Task D: MDS (top-10 only)**  | 2D MDS map of top-10 brands (distance = 1/lift)                                                                                  |               |         |      |              |            |
| **Task E: Insights (C & D)**   | Business insights from lift + MDS                                                                                                |               |         |      |              |            |
| **Task F: Top 5 attributes**   | Frequency table of top-5 car attributes; associations to brands                                                                  |               |         |      |              |            |
| **Task G: Insights (F)**       | Client advice from attribute–brand associations                                                                                  |               |         |      |              |            |
| **Task H: Aspirational brand** | Identify most aspirational brand + business implications                                                                         |               |         |      |              |            |
| **Final Integration**          | Combine all steps (A–H + scraper) into **one clean notebook** with results, frequency tables, lift table, MDS plot, and insights |               |         |      |              |            |
