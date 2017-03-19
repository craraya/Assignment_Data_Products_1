Abstract
--------

This document was scribed with a use plotly package intention and
explain Moving Averages formula

Moving Averages
---------------

In statistics, a moving average (rolling average or running average) is
a calculation to analyze data points by creating series of averages of
different subsets of the full data set.

### Simple moving average

In financial applications a simple moving average (SMA) is the
unweighted mean of the previous n data. However, in science and
engineering the mean is normally taken from an equal number of data on
either side of a central value.

$$SMA = \\frac{1}{n}\\sum\_{i=0}^{n-1} X\_{M-i}$$

### Exponential Moving Average

An exponential moving average (EMA), also known as an exponentially
weighted moving average (EWMA), is a type of infinite impulse response
filter that applies weighting factors which decrease exponentially.

*E**M**A*<sub>*t*</sub> = *E**M**A*<sub>*t* − 1</sub> − *α* × (*X*<sub>*t*</sub> − *E**M**A*<sub>*t* − 1</sub>)

### A Plot with both

> SMS in grey line and EMA in blue line.
