

## Data Visualization

### Concepts
[What is the difference between drawing plots using plot, axes or figure in matplotlib?](https://stackoverflow.com/questions/37970424/what-is-the-difference-between-drawing-plots-using-plot-axes-or-figure-in-matpl)
- figure: like a canvas, where to specify the dimensions and the possibly background setting; use figure in two ways 1) place other objects on it (mostly axes, but also text tables etc) 2) save its content with savefig
- axes: like a sort of Swiss Army Knife, a handy object that offers a tool for everything (eg: .plot; .scatter; .hist etc); can place one, two, ... many axes inside a figure using one of many different methods 
- the plt interface: the plt procedural interface was originally developed to mimic the MATLAB interface, but is not really different from the object oriented interface, even if we don't make direct reference to the main objects (figure, axes) these objects are automatically instantiated and each plt method is translated to a call of one of the methods of the underlying fundamental objects (eg: plt.plot is a hidden_axes.plot; plt.savefig is a hidden_figure.savefig)


### Seaborn CheatSheet
<img width="546" alt="Screen Shot 2022-06-23 at 10 25 25" src="https://user-images.githubusercontent.com/49216429/175323018-6eccc35a-5829-4b4b-936c-1ad4f462b230.png">

Plotting Functions
- [Visualize Statistical Relationships](https://seaborn.pydata.org/tutorial/relational.html)
1) Scatter Plots [scatterplot(); relplot(x=?, y=?, hue=?, kind='scatter', data=data)] : Relate Variables
2) Line Plots[lineplot(); relplot(x=?, y=?, kind='line', data=data] : Emphasize Continuity
3) Line Plots with Confidence Interval : Aggregation and Representing Uncertainty
4) FacetGrid [relplot(x=?, y=?, hue=?, col=?, data=data)] : Relationship between two variables depending on more than one other variable

- [Visualize Distributions of Data](https://seaborn.pydata.org/tutorial/distributions.html)
1) Plot Univariate Histograms
2) Kernel Density Estimation
3) Empirical Cumulative Distributions
4) Visualize Bivariate Distributions
5) Distribution Visualization in other settings

- [Plot with Categorical Data](https://seaborn.pydata.org/tutorial.html)
1) Categorical Scatterplots
2) Distribution of Observations within Categories
3) Statistical Estimation within Categories
4) Plot "wide-form" data
5) Show Multiple Relationships with Facets

- [Visualize Regression Models](https://seaborn.pydata.org/tutorial/regression.html)
1) Functions to Draw Linear Regression Models
2) Fitting Different Kinds of Models
3) Condition on Other Variables
4) Control the Size and Shape of the plot
5) Plot a regression in other contexts


[Plotting Aesthetics](https://seaborn.pydata.org/tutorial/aesthetics.html)
- Figure Stypes
- Remove Axes Spines
- Temporarily Set Figure Style
- Override Elements of Seaborn Styles
- Scale Plot Elements

Example Gallery
- [LM Plot](https://seaborn.pydata.org/examples/anscombes_quartet.html)
- [Scatter Plot](https://seaborn.pydata.org/examples/different_scatter_variables.html)
- [Line Plot](https://seaborn.pydata.org/examples/errorband_lineplots.html)
- [Dis Plot](https://seaborn.pydata.org/examples/faceted_histogram.html)
- [Hist Plot](https://seaborn.pydata.org/examples/histogram_stacked.html)
- [Box Plot](https://seaborn.pydata.org/examples/grouped_boxplot.html)
- [Join Plot](https://seaborn.pydata.org/examples/hexbin_marginals.html)
- [Pair Plot](https://seaborn.pydata.org/examples/scatterplot_matrix.html)
- [Horizontal Bar Plot](https://seaborn.pydata.org/examples/part_whole_bars.html)
- [Annotated Heatmaps](https://seaborn.pydata.org/examples/spreadsheet_heatmap.html)


<!-- ### Scikit-learn Cheatsheet -->
