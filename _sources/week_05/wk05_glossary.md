# Week 5 glossary

## Online resources

The official matplotlib documentation can be found in [https://matplotlib.org/stable/api/index.html](https://matplotlib.org/stable/api/index.html) (*note*: we are using the "axes interface")

In addition, you may find the cheatsheets provided by matplotlib ([https://matplotlib.org/cheatsheets/](https://matplotlib.org/cheatsheets/)) useful.

## Numpy syntax

+ `+`, `-`, `*`, `/`, `//`, `%`, `**`: arithmetic operators on multi-dimensional numpy arrays<br><br>

+ `[]`: indexing operators on multi-dimensional numpy array
+ `:` : operator to create slicing object of form _start_:_stop_:_step_

## Numpy functions and methods

### Numpy array methods

+ `.reshape()`: reshape an numpy array
+ `.flatten()`: flatten a multi-dimensional array to 1D
+ `.tranpose()`: transpose the rows and columns of a 2D numpy array

### Numpy mapping functions

+ `np.exp()`, `np.sin()`, etc. Functions that applying a mapping to each element of a multi-dimensional array (for a more complete list, see the glossary of week 4)

### Numpy reduction functions

+ `np.mean()`, `np.sum()`, etc. Functions that apply reduction along particular axis / axes or across the whole multi-dimensional array (for a more complete list, see the glossary of week 4)

## matplotlib functions

### Creating and showing figures and axes

+ `plt.figure()`: create a new figure
+ `fig.add_subplot()`: add new axes object to an existing figure
+ `plt.show()`: show a figure already created<br><br>

### Making different types of visualization

+ `ax.plot()`: create a line plot on the axes instance `ax`
+ `ax.scatter()`: create a scatter plot on the axes instance `ax`
+ `ax.bar()`: create a bar plot on the axes instance `ax`

### Axes and titles

+ `ax.set_title()`: set the title of the figure, for the axes instance `ax`
+ `ax.set_xlabel()`, `ax.set_ylabel()`: set the labels for x- and y-axis, respectively, for the axes instance `ax`
+ `ax.set_xlim()`, `ax.set_ylim()`: set the x- and y-axis limits, respectively, for the axes instance `ax`
+ `ax.set_xticks()`, `ax.set_yticks()`: set the ticks for x- and y-axis, respectively, for the axes instance `ax`
+ `ax.tick_params()`: set the parameters for ticks (e.g., font size for tick labels), for the axes instance `ax`
+ `ax.grid()`: create a grid overlay for the axes instance `ax`
+ `ax.legend()`: create a legend for the axes instance `ax`