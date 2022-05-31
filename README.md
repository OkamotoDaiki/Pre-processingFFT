# Pre-process until FFT
Performs pre-processing from time series data to FFT.


# Features
It has a function that can automatically increase the length of data to the power of 2 with zero padding.
It can be used by converting the ZeroPadding class into an object and executing the process() function.


# Requirement

* Python 3.8.10
* numpy 1.21.4


# Installation

The data object is one-dimensional array.

```python
import FFTTool
data = np.array([]) #example
fft_tool = FFTTool.ZeroPadding(data)
new_data = fft_tool.process()
```

# Author
* Oka_D
* okamotoschool2018@gmail.com