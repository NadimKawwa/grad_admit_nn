# Content: Neural Nets
## Project: Graduate Admissions


### Summary

Can you predict graduate school admittance using a neural network?
This case considers three features: GRE, GPA, and rank. Since the data is small, gradient descent is implemented without batching.
In a later stage back propagation is included to enhance prediction accuracy.

### Install

This project requires **Python 3.6** or more recent and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/index.html)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

### Code

Template code is provided in the `admissions_gsd_backprop.ipynb` notebook file.

## Data

The graduate school data is included as a selection of 400 data points collected on data found from UCLA. More information can be found on [UCLA](https://stats.idre.ucla.edu/stat/data/binary.csv) or on [kaggle.com](https://www.kaggle.com/malapatiravi/graduate-school-admission-data).


**Features**
1) `admit`: 1 for admitted, 0 for rejected;
2) `gre`: GRE score in old format, highest score possible is 800;
3) `gpa`: grade point average, highest possible is 4.0;
4) `rank`: university ranking, rank 1 is most prestigious;
