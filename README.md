# Classifying signals with Fourier and Wavelet features

We'll use the [NASA turbofan engine dataset](http://ti.arc.nasa.gov/c/6/) to try to classify the system health into 3 states: healthy, needs attention, critical. We'll use the fourier transform and discrete wavelet transforms provided by the Python libraries, `scipy.fftpack` and `pywt`, for feature extraction.
