# Data-analysis-visualization

Data visualisation: seven questions, each answered with a different kind of chart using real-world datasets.

## Questions and charts

| # | Chart | Dataset | Task |
|---|---|---|---|
| 1 | Line chart | Gapminder | Population of France, UK, Italy, Germany and Spain, 1952–2007 |
| 2 | Scatter plot | Diamonds (53,000+ stones) | Carat vs price for clarity `SI2`, colour `E`, coloured by cut |
| 3 | Histogram + box plot | Exoplanets (1,000+ planets) | Distribution of planet masses; median vs maximum; mass vs orbital period |
| 4 | Bar chart | Job Automation Probability (Oxford, 2013) | 25 jobs needing a bachelor's degree that are most likely to be automated |
| 5 | Map | Nuclear waste sites on US campuses | Sites shown as clickable markers on a US map (Folium) |
| 7 (optional) | Bar, line, heat map, choropleth, word cloud, marker cluster | US police deaths, 1984–2016 | Deaths per year, by state, by location and by cause |

## How to run

All datasets are downloaded from public URLs inside the notebook.

```bash
pip install numpy pandas matplotlib seaborn plotly folium wordcloud
jupyter notebook data_analysis_visualization_practice.ipynb
```

## Technologies

Python, pandas, NumPy, Matplotlib, seaborn, Plotly, Folium, WordCloud, Jupyter Notebook
