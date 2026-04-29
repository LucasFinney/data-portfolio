# DataCamp Code

A commonplace book and portfolio for experiments, projects, and course work relating to data science and data analysis. Covers data manipulation, visualization, Python programming, and real-world analysis projects.

---

## Root-Level Notebooks

| Notebook | Description |
|---|---|
| `inner_joins_31026.ipynb` | Follows the "Joining Data with Pandas" DataCamp course. Demonstrates inner joins to find the alderman of the most populous ward in Chicago. Includes notes on sourcing government data via Socrata. |
| `inner_joins_31126.ipynb` | Playground for experimenting with small toy datasets to verify understanding of join mechanics. |
| `genres_and_sequels_31226.ipynb` | Multi-table merge exploration using DataCamp movie datasets to identify which genre has the most sequels. |
| `Python_Review_31226.ipynb` | Review notes covering general Python and Pandas fundamentals. |
| `general_notes_and_snips.ipynb` | Scrapbook of useful code snippets and techniques, especially for tricky or non-obvious problems. |

---

## Courses

### Joining Data with Pandas
> Notes in `Data Notes/Joining Data with Pandas/`

Detailed reference notes and worked examples for every join type:
- Inner, Left, Right, Outer joins
- Semi-join and Anti-join
- Visual diagrams and code examples for each

### Exploratory Data Analysis in Python
> `Exploratory Data Analysis in Python/`

Four-notebook module covering the full EDA workflow:
- Getting to know a dataset (summary statistics, dtypes)
- Data cleaning and imputation
- Identifying relationships and correlations
- Turning findings into actionable insights

### Intro to Data Viz with Matplotlib
> `Intro to data viz with Matplotlib/`

Four-notebook course covering:
- Matplotlib basics
- Plotting time-series data
- Quantitative comparisons and statistical visualizations
- Preparing publication-ready figures

### Intro to Data Viz with Seaborn
> `Intro to data viz with Seaborn/`

Six-notebook course covering:
- Seaborn fundamentals
- Visualizing two quantitative variables
- Visualizing categorical vs. quantitative variables
- Integration with Pandas DataFrames
- Plot customization and styling

### Intro to Functions in Python
> `Intro to functions in Python/`

Three-notebook course covering:
- Writing functions
- Default arguments, variable-length arguments, and scope
- Lambda functions and error handling

### Python Toolbox
> `Python Toolbox/`

Three-notebook course on advanced Python patterns:
- List comprehensions and generators
- Iterators and iteration patterns
- Case study applying these tools

---

## Projects

### Analyzing Crime in Los Angeles
> `Projects/Analyzing Crime in Los Angeles/`

End-to-end analysis of crime patterns in LA using a 27 MB dataset (`crimes.csv`). Outputs and visualizations are saved to the `Outputs/` subdirectory.

### Nobel Prize Winners
> `Projects/NobelPrizeWinners/`

Analysis of historical Nobel Prize winner data (`data/nobel.csv`), exploring trends across categories, countries, and time.

---

## Reference Materials

### Cheatsheets
> `Cheatsheets/`

- Pandas cheat sheet
- Matplotlib cheat sheet
- Exploratory Data Analysis in Python cheat sheet
- Data Analysis Workflow diagram

### Data Notes
> `Data Notes/`

Markdown notes on key topics including `.merge()` usage and join types. `TO-DO.md` tracks topics still to be covered (concat, query, `merge_ordered()`, `merge_asof()`, melt).

---

## Datasets
> `datasets/`

~219 MB of datasets used across projects and exercises, including:

| Dataset | Size | Topic |
|---|---|---|
| `WDICSV.csv` | 188 MB | World Development Indicators |
| `crimes.csv` | 27 MB | Los Angeles crime data |
| `raw-responses.csv` | 2.2 MB | Survey responses |
| `planes.csv` | 1.1 MB | Aviation data |
| `divorce.csv` | 195 KB | Divorce prediction |
| `ds_salaries_clean.csv` | 29 KB | Data science job salaries |
| `countries-of-the-world.csv` | 38 KB | Country statistics |
| `seattle_weather.csv` / `austin_weather.csv` | — | Weather data |
| `student-alcohol-consumption.csv` | 37 KB | Youth survey |
| `mpg.csv` | 21 KB | Vehicle fuel economy |
| `movies.p` / `movie_to_genres.p` / `sequels.p` | — | Movie metadata (pickled) |
