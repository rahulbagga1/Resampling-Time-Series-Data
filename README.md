# Resampling Time Series Data

* Time series data is recorded with different frequencies. For example, a device is recording data at 200Hz i.e 200 data points in one second which means 1 data point in 5 ms.
* If data is recorded for 1 hour then there gonna be quite large amount of data.
* And, 200Hz data cannot make that much good model.
* Downsampling is done in which some in between time steps are aggregated into single time step.
* It is similar to moving average.
* Numpy and Pandas are used.
