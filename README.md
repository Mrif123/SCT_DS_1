# India Population Distribution Analysis (2022)

This project analyzes and visualizes India's population distribution across different age groups using Python and Matplotlib. The data is based on age-wise population estimates from 2022.

## 📁 Files

- `Population_Analysis.ipynb`: Jupyter Notebook containing all data processing and visualizations.
- `India_Population_By_Age_Group_2022.csv`: Dataset with 5-year age groups and population estimates (in millions).
- `Bar_Chart_Population_By_Age_Group.png`: Bar chart of population across age groups.
- `Line_Chart_Population_By_Age_Group.png`: Line chart showing population trend by age group.
- `Pie_Chart_Age_Groups.png`: Pie chart of 3 grouped age categories (0–20, 21–64, 65+).
- `Pie_Chart_All_Age_Groups.png`: Pie chart for all 5-year age groups.
- `Histogram_Population_By_Age.png`: Histogram created from simulated individual age data.

## 📊 Features

- Bar chart showing population by 5-year age bands.
- Line chart depicting trends in population across age groups.
- Pie charts:
  - Based on broad age categories (0–20, 21–64, 65+)
  - Based on all detailed age groups
- Histogram simulated from grouped data to visualize population spread across individual ages.

## 📦 Requirements

- Python 3.8+
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- numpy

Install dependencies using pip:

```bash
pip install pandas matplotlib seaborn numpy
```

## 🧠 Methodology

- The dataset contains age groups and corresponding population counts.
- A histogram is created by simulating individual ages using `numpy.random.randint` from grouped data.
- All plots are generated using `matplotlib` and `seaborn`.

## 📌 How to Run

1. Open `Population_Analysis.ipynb` in Jupyter Notebook or Google Colab.
2. Run all cells to generate visualizations.
3. Save or modify plots as needed.

## 📈 Example Outputs

- ![Bar Chart](Bar_Chart_Population_By_Age_Group.png)
- ![Histogram](Histogram_Population_By_Age.png)

## 📚 License

This project is open for educational and analytical use. Attribution appreciated.