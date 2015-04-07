* [Multicollinearity statistics with SPSS] (http://www.thejuliagroup.com/blog/?p=1405)

* [scipy.stats.mstats.normaltest — SciPy v0.14.0 Reference Guide](http://docs.scipy.org/doc/scipy-0.14.0/reference/generated/scipy.stats.mstats.normaltest.html)

* [scipy.stats.ttest_ind — SciPy v0.14.0 Reference Guide]
(http://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html)

* [scipy.stats.mannwhitneyu — SciPy v0.14.0 Reference Guide](http://docs.scipy.org/doc/scipy-0.14.0/reference/generated/scipy.stats.mannwhitneyu.html)

* [A post from a previous student as highlighted in your blog](http://nbviewer.ipython.org/url/www.asimihsan.com/articles/Intro%20to%20Data%20Science%20-%20Final%20Project.ipynb)

* [python - How do you change the size of figures drawn with matplotlib? – Stack Overflow](http://stackoverflow.com/questions/332289/how-do-you-change-the-size-of-figures-drawn-with-matplotlib): 

```figure(num=None, figsize=(8,6), dpi=80, facecolor='w', edgecolor='k')```

* [numpy.where — NumPy v1.8 Manual](http://docs.scipy.org/doc/numpy/reference/generated/numpy.where.html):np.where(x < 5, x, -1)

* [dates — Matplotlib 1.4.0 documentation](http://matplotlib.org/api/dates_api.html)
```
week from matplotlib.dates import MO, TU, WE, TH, FR, SA, SU
loc = WeekdayLocator(byweekday=(MO, SA))
```

* [python - How do I convert dates into ISO-8601 DateTime format in a Pandas dataframe - Stack Overflow]
(http://stackoverflow.com/questions/18618288/how-do-i-convert-dates-into-iso-8601-datetime-format-in-a-pandas-dataframe)
```df['q_date'].apply( lambda x: pd.datetools.parse(x).strftime('%Y%m%dT%H:%M%SZ'))```

* [api example code: barchart_demo.py — Matplotlib 1.4.0 documentation](http://matplotlib.org/examples/api/barchart_demo.html)
```
ind = np.arange(N)
width = 0.35
bars fig, ax = plt.subplots() rects1 = ax.bar(ind, menMeans, width,
color='r', yerr=menStd)
ax.set_title('Scores by group and gender')
ax.set_xticks(ind+width)
ax.set_xticklabels( ('G1', 'G2', 'G3', 'G4', 'G5') )
ax.legend( (rects1[0], rects2[0]), ('Men', 'Women') )
```

* [Summarizing Data in Python with Pandas](http://bconnelly.net/2013/10/summarizing-data-in-python-with-pandas/)
```
bygroup_treatment['RelativeFitness'].describe()
bygroup_treatment['RelativeFitness'].aggregate(np.sum)
```

* [ŷhat | ggplot for python](http://blog.yhathq.com/posts/ggplot-for-python.html)
```
p = ggplot(diamonds, aes(x='price')) p + geom_density()+ \
facet_grid("cut","clarity")
```

* [An introduction to Statistics](http://work.thaslwanter.at/Stats/StatsIntro.pdf)
```df[’Eins’] = np.ones(( len(df), ))```

* [python - Editing the date formatting of x-axis tick labels in matplotlib - Stack Overflow](http://stackoverflow.com/questions/14946371/editing-the-date-formatting-of-x-axis-tick-labels-in-matplotlib)
`
```
myFmt = mdates.DateFormatter('%d')
ax.xaxis.set_major_formatter(myFmt)
```

* [datetime - Plotting dates on the x-axis with Python's matplotlib- Stack Overflow](http://stackoverflow.com/questions/9627686/plotting-dates-on-the-x-axis-with-pythons-matplotlib)
```new_x = dates.datestr2num(date)# where date is '01/02/1991'```

* [Writing mathematical expressions — Matplotlib 1.3.1 documentation](http://matplotlib.org/1.3.1/users/mathtext.html)

* [Sharing an Ipython notebook via gist and nbviewer – YouTube](https://www.youtube.com/watch?v=eYVCH61fKyY)
