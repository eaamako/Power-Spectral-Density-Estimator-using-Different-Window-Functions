# Power-Spectral-Density-Estimator-using-Different-Window-Functions
This repository contains code that demonstrates how to estimate the power spectral density of a signal using different window functions in Python. The code imports the following libraries:  numpy, scipy, matplotlib

The code imports required libraries, defines a function called "periodogram" to compute the power spectral density of a signal using different window functions, and defines a main function that loads a signal from a file, sets the sampling frequency, and applies the periodogram function to the signal using different window functions. The main function then plots the power spectral density of the signal using each window function for the original and zero-padded FFT lengths. The output of the code is a set of plots showing the power spectral density of the signal using different window functions.

![image](https://user-images.githubusercontent.com/115730728/234069152-4d021335-5cee-46c6-bdd6-c2d558abad3c.png)

The code is a Python script that computes and plots the periodogram of a signal using different window functions. The script first loads the signal and sets the sampling frequency. It then defines a function called periodogram() that computes the periodogram of a signal using a given window function. The function takes three arguments:

•	x: The signal to be analyzed.

•	window: The window function to be used.

•	N_fft: The FFT length.

The function returns a power spectrum of the signal.

The script then defines a dictionary of window functions. The dictionary contains the following window functions:
•	Rectangular: A rectangular window function.
•	Hann: A Hann window function.
•	Hamming: A Hamming window function.
•	Blackman: A Blackman window function.

The script then chooses a window function and plots the periodogram of the signal for the original number of frequency points. The script then plots the PSD for the zero-padded number of frequency points.

The script produces the following plots:
•	[Image of the periodograms of the signal using different window functions]
•	[Image of the PSDs of the signal using different window functions]

The plots show that the different window functions have different effects on the periodogram of the signal. The rectangular window function has the most noise, while the Blackman 
window function has the least noise. The Hann and Hamming window functions have intermediate levels of noise.
