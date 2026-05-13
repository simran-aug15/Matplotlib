# 📊 Matplotlib Mastery — From Basic to Advanced Visualizations

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-orange?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

A structured, hands-on collection of Jupyter notebooks covering **Matplotlib** from the ground up — starting with fundamental 2D plots and progressing to advanced 3D visualizations and DataFrame-driven charts.

---

## 📁 Repository Structure

```
matplotlib-mastery/
│
├── basic/
│   ├── 2d_lineplot.ipynb
│   ├── scatterplot.ipynb
│   ├── bar_chart.ipynb
│   ├── histogram.ipynb
│   └── piechart.ipynb
│
└── advanced/
    ├── colored_scatterplot.ipynb
    ├── subplot.ipynb
    ├── 3D_scatterplot.ipynb
    ├── 3D_surface_plot.ipynb
    └── dataframeplot.ipynb
```

---

## 🟢 Basic Visualizations

### 📈 2D Line Plot — `2d_lineplot.ipynb`
An introduction to one of the most fundamental chart types. Covers:
- Plotting single and multiple lines
- Customizing line styles, colors, and markers
- Adding titles, axis labels, and legends
- Setting axis limits and grid lines

**Key function:** `plt.plot()`

---

### 🔵 Scatter Plot — `scatterplot.ipynb`
Visualize relationships between two continuous variables. Covers:
- Basic scatter plot creation
- Adjusting marker size and transparency (`alpha`)
- Adding color to distinguish data points
- Interpreting correlation patterns

**Key function:** `plt.scatter()`

---

### 📊 Bar Chart — `bar_chart.ipynb`
Compare categorical data clearly and effectively. Covers:
- Vertical and horizontal bar charts
- Grouped and stacked bar charts
- Adding value labels on bars
- Customizing bar colors and edge styles

**Key function:** `plt.bar()` / `plt.barh()`

---

### 📉 Histogram — `histogram.ipynb`
Understand frequency distributions of continuous data. Covers:
- Choosing the right number of bins
- Normalizing histograms (density vs. count)
- Overlapping histograms for comparison
- Cumulative histogram plotting

**Key function:** `plt.hist()`

---

### 🥧 Pie Chart — `piechart.ipynb`
Display proportional data in a circular layout. Covers:
- Basic pie chart with percentage labels
- Exploding slices for emphasis
- Donut chart variation
- Custom colors and shadow effects

**Key function:** `plt.pie()`

---

## 🔴 Advanced Visualizations

### 🎨 Colored Scatter Plot — `colored_scatterplot.ipynb`
Extend scatter plots with a third dimension using color. Covers:
- Mapping a third variable to color using `c` and `cmap`
- Using colorbars to indicate scale
- Combining size and color encoding for multi-variable plots
- Choosing perceptually uniform colormaps

**Key function:** `plt.scatter()` with `cmap` and `colorbar()`

---

### 🗂️ Subplot — `subplot.ipynb`
Arrange multiple plots in a single figure for side-by-side comparison. Covers:
- `plt.subplot()` and `plt.subplots()` layout
- Sharing axes across subplots
- Custom figure sizes and spacing (`tight_layout`, `GridSpec`)
- Mixed chart types in one figure

**Key functions:** `plt.subplots()`, `fig.add_subplot()`, `GridSpec`

---

### 🌐 3D Scatter Plot — `3D_scatterplot.ipynb`
Visualize three-dimensional relationships between variables. Covers:
- Setting up a 3D axis with `mpl_toolkits.mplot3d`
- Plotting `(x, y, z)` coordinates
- Rotating and viewing 3D plots from different angles
- Color-mapping the third dimension

**Key function:** `ax.scatter()` on an `Axes3D` object

---

### 🏔️ 3D Surface Plot — `3D_surface_plot.ipynb`
Render continuous mathematical surfaces in 3D space. Covers:
- Generating meshgrid data with `np.meshgrid()`
- Plotting surfaces with `plot_surface()`
- Applying colormaps and wireframe overlays
- Visualizing mathematical functions (e.g., sine waves, paraboloids)

**Key function:** `ax.plot_surface()`

---

### 🐼 DataFrame Plot — `dataframeplot.ipynb`
Leverage Pandas' built-in `.plot()` interface backed by Matplotlib. Covers:
- Plotting directly from a `pd.DataFrame`
- Line, bar, scatter, histogram, and box plots via `.plot(kind=...)`
- Multi-column and grouped plotting
- Customizing Pandas plots with Matplotlib commands

**Key function:** `df.plot()`, `df.plot.bar()`, `df.plot.scatter()`

---

## 🛠️ Requirements

Install all dependencies with:

```bash
pip install matplotlib numpy pandas jupyter
```

For 3D plots, `mpl_toolkits` is included with Matplotlib — no extra install needed.

| Package      | Version     |
|-------------|-------------|
| Python       | ≥ 3.8       |
| matplotlib   | ≥ 3.5       |
| numpy        | ≥ 1.21      |
| pandas       | ≥ 1.3       |
| jupyter      | ≥ 1.0       |

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/matplotlib-mastery.git
   cd matplotlib-mastery
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Start with the basics** — open any notebook inside the `basic/` folder and run cells top to bottom.

---

## 💡 Learning Path

```
2D Line Plot → Scatter Plot → Bar Chart → Histogram → Pie Chart
      ↓
Colored Scatter → Subplots → 3D Scatter → 3D Surface → DataFrame Plot
```

Follow this order for the smoothest progression from beginner to advanced concepts.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add new notebook examples
- Improve existing explanations
- Fix bugs or typos

Please open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
