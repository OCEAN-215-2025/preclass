# Using jupyter notebook

## Jupyter notebooks: what and why

In this course we'll execute python codes mainly using Jupyter notebooks. These are files with `.ipynb` extensions. The advantage of Jupyter notebooks are:

+ You can executes python codes in small units, which makes debugging easier.
+ You can executes python codes interactively, i.e., you can switch between debugging and executing fairly seamlessly.
+ You can mix rich-formatted texts with python code within the same file. This is especially useful if you want to documnent what your codes is doing.

## Creating, uploading, downloading, and opening a new jupyter notebook

+ To create a new jupyter notebook in Jupyterhub, click on the `+` symbols either at the top of the main panel or at the top of the left panel, which brings up a launcher. Then, at the top section of the main panel, just click on the icon that says "Python 3 (ipykernel)"
+ To upload a file onto jupyter hub, all you need to do is to drag the file from your desktop / file browser to the left pane of the jupyter hub
+ To download a file onto your computer, right click on the `.ipynb` file from the left pane, and select download
+ To edit an existing jupyter notebook file, left click on the file on the left pane and it will be displayed on the main panel.

## Basic jupyter notebook manipulation

A jupyter notebook is comprised of cells. There are 3 types of cells: raw, markdown, and code. In this course we will mainly deal with the latter 2 types. Visually, a code cell is distinguished from the markdown cell by a gray background. The markdown cell is used for displaying richly-formatted texts, while code cell is used to execute python codes.

In general, there are two modes of operation in a jupyter notebook: the **command mode** and the **edit mode**. The former is for cell-level operations while the latter is for editing the content within a cell. If you see a flashing cursor in your notebook, you are likely in edit mode. In addition, the current cell being edited is usually indicated by a tight blue line frame, whereas in command mode the blue frame extends all the way to the left.

A few operations that are useful in command mode:
+ `m` converts the current cell into a markdown cell
+ `y` converts the current cell into a code cell
+ `a` insert a cell above the current cell
+ `b` insert a cell below the current cell
+ `c` copy the content of the current cell, and `v` pastes it
+ `d` + `d` delete the current cell
+ `z` undo the previous action

## Markdown formatting

In markdown certain characters have special meaning. Some useful examples:
+ To create a list, start the line with a `+`, followed by a space
+ To set a block of texts in boldface, surround the block with a pair of `**`
+ To italicize a block of texts, surround the block with a pair of `_`
+ To set a block of text in monospace, surround the block with a pair of `` ` ``
+ To create headings, start the line with a sequence of `#`, followed by a space (the more `#` to lower the heading in the heading hierarchy)

## Comments within code cell

Within a code cell you may occasionally see lines that start with a `#` symbol. Such lines serve the purpose of **comments** in the python language. In other words, content to the right ofthe `#` symbol is ignored by the python executable when the cell is run.

In fact, you can start a comment with a `#` in the middle of a line. The content to the left of the `#` symbol is executed as code, whereas texts after the `#` symbol are ignored.

In jupyter notebook the role of comments somewhat overlaps with that of a markdown cell. However, in a python script where every line is code, comments are useful in helping a human reader to understand what the code is doing.