# Pandas and MatPlotLib exploration
I spent a couple weeks exploring how to code in Python. I have never coded before and so I am going for a zero to hero moment. I don't expect myself to become a coding master, but I have a direction in mind that I would like to explore.

A few days ago, I just finished up my first Python project called Build A Graph. It just took user input and then created a graph using basic Python Sytax. While not a master, I felt like I had the basics done enough to move onto the next thing. After python basics, I wanted to understand Numpy, Pandas and MatplotLib as these are critical for data science. I was learning about these in parallel to the Python basics, so I felt ready to explore them on my own.

### This "project"
While I wouldn't necessarily call this a full on project, this was my first time importing data from a CSV I found, cleaning the data from missing data and unwanted data, then indexing and plotting various graphs for trends I wanted to see.

Nothing groundbreaking in this, but it helped me become more comfortable with pandas DataFrames as well as Jupyter Notebooks.

## Challenges

### Import
Right off the bat, importing data from a CVS was harder than expected.
~~~
#I thought it was this simple
import pandas as pd
pd.read_csv('file name.csv')
~~~
The problem is that I could never get the file name right. I found it really helped to put the data in the same folder as the project.

### Cleaning
I'm not 100% sure if this is actually considered cleaning, but I spent a majority of time making the index correct, getting rid of NaN values, renaming columns, and filtering out columns of data I did not want. This took the most time but left me with a much more useful dataset.

### Subplots
I never made mutiple graphs at once. While the graphs I made aren't the best, it at least allowed me to see trends I wouldn't have otherwise seen. Graphing along with calculated indexing provides great insight

### Changing data type
The data apparently imported as Objects instead of floats. It took a little to figure out, but the solution was pretty simply since everything needed to be converted and not individual columns. 
~~~
df.
