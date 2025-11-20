# Movie-Recommendation
This project builds a movie recommendation system based on Pixie-inspired random walk algorithms.
Objective
To recommend movies similar to a given title by simulating random walks over a
user–movie bipartite graph, inspired by Pinterest’s Pixie engine.
Files Included
- `Movie_Recommendation.ipynb` — Main notebook with all code
- `movies.csv`, `ratings.csv`, `users.csv` — Dataset files
- `Pixie_Algorithm_Explanation.md` — 3–5 paragraph algorithm explanation
- `Recommendation_Report.md` — Summary of approach, dataset, and results
How to Run
1. Open the notebook `Movie_Recommendation.ipynb`
2. Run all cells to build the graph and execute recommendations.
3. Use:
```python
weighted_pixie_recommend("Movie Title (Year)", walk_length=15, num=5)
