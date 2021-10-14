# sinaplot
Sinaplot implementation in Python adapted from https://github.com/mparker2/seaborn_sinaplot

Adapted to include a boxplot in the middle of the sinaplot.

Difference in implementation: ```showboxplot=True``` to draw boxplots in the sinaplots.

example use: ```sinaplot(x='allele', y=value, data=df, showboxplot=True, point_size=1, width=0.95, scale='area', color='gray')```
