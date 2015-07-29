
# Notes

# Getting started:

## Python libraries

We will use Pandas to get our data into a dataframe and then Bokeh for some basic exploratory visualization.

* To install Bokeh for python run:

```
pip install bokeh
```

* Or if you use Ananconda to manage your libraries you can run:

```
conda install bokeh
```

## (Optional) Installation notes:

### Pandas 

If you don't already have Pandas installed run:

pip install pandas

### Errors I ran into

On linux I had a problem the first time I went to run Bokeh..

Got error `Exception Value: cannot import name TimeoutStateError` and then updated the request library

Ran :

```
pip install requests --upgrade
```
(a useful discussion here: http://stackoverflow.com/questions/25713689/exception-value-cannot-import-name-timeoutstateerror-when-import-geocoder)


# Quick examples

We'll use ipython notebook to run out Bokeh plots, so from this directory start up Ipython Notebook (or Jupiter) by typing:
```
ipython notebook
```

Navigate to the web browser that opened up and we'll work from there.

