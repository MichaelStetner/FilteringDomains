# FilteringDomains
Filtering in the time domain vs frequency domain. Analysis with LIGO dat

In signal processing, filters attenuate unwanted frequencies in the stopband, leaving behind the signal of interest in the passband. An ideal filter removes all signal in the stop band and leaves the signal in the passband unchanged. Such a filter can be realized in the frequency domain. After taking the Fourier transform of the signal, set the amplitude of the stopband to zero and then take the inverse transform.

Nevertheless, filtering is often performed in the time domain, for example with a Butterworth Filter. A Butterworth Filter is not ideal because it has a slow rolloff, while a filter in the frequency domain can have a perfect cutoff. Why is a Butterworth Filter used? What are the advantages of filtering in the time domain vs. the frequency domain?

To answer these questions, we will use some data from the LIGO Open Science Center. This is the data from the first observation of a gravitational wave. I chose this data because there is a very good theoretical prediction for what the data should look like, and the data is a good match when using a Butterworth filter.


