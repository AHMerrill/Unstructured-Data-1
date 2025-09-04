## Links to code notebooks:

| Notebook        | Colab |
|-----------------|-------|
| `scraper_zm.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AHMerrill/Unstructured-Data-1/blob/main/scraper_zm.ipynb) | 
| `vectorizer_lift_MDS_zm.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AHMerrill/Unstructured-Data-1/blob/main/vectorizer_lift_MDS_zm.ipynb) |
| `zipf_zm.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AHMerrill/Unstructured-Data-1/blob/main/zipf_zm.ipynb) | 

## In colab, if you make changes to notebooks, use "save in github" at the top of the page to re-commit.
## Download any created csv or other files and re-commit those manually.


| Task                           | What                                                                                                                             | File/Notebook | Done by | Date | Validated by | Notes / PR |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------- | ---- | ------------ | ---------- |
| **Scraper implemented**        | Python scraper; handles forum HTML & threading; drops block quotes                                                               | scraper_zm.ipynb              | Zan        | 4 Sep     |              |            |
| **Scrape 8–10k posts**         | CSV with `userid,date,message` columns produced                                                                                  |  scraper_zm.ipynb; car_comments_zm.csv             |  Zan       | 4 Sep     |              |            |
| **Toy data check**             | Tiny CSV + hand-calculated lift compared to code                                                                                 |               |         |      |              |  From Zan: I kind of did this, but I'm not sure I did it right... So TBD on whether all of my code is flawed...          |
| **Task A: Zipf test**          | OLS regression on log–log; slope test; plot top-100 words vs theory                                                              |  zipf_zm.ipynb             | Zan        | 4 Sep     |              |            |
| **Task B: Top-10 brands**      | Stopwords removed; models collapsed into brands; 1 mention/msg                                                                   | vectorizer_lift_MDS_zm.ipynb              | Zan        | 4 Sep      |              |            |
| **Task C: Lift (top-10 only)** | Lift table for top-10 brands                                                                                                     | vectorizer_lift_MDS_zm.ipynb              | Zan        | 4 Sep     |              |            |
| **Task D: MDS (top-10 only)**  | 2D MDS map of top-10 brands (distance = 1/lift)                                                                                  | vectorizer_lift_MDS_zm.ipynb              | Zan        | 4 Sep     |              |            |
| **Task E: Insights (C & D)**   | Business insights from lift + MDS                                                                                                |               |         |      |              |            |
| **Task F: Top 5 attributes**   | Frequency table of top-5 car attributes; associations to brands                                                                  |               |         |      |              |            |
| **Task G: Insights (F)**       | Client advice from attribute–brand associations                                                                                  |               |         |      |              |            |
| **Task H: Aspirational brand** | Identify most aspirational brand + business implications                                                                         |               |         |      |              |            |
| **Final Integration**          | Combine all steps (A–H + scraper) into **one clean notebook** with results, frequency tables, lift table, MDS plot, and insights |               |         |      |              |            |
