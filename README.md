# Filtering_Monalisa
Use of Image processing to produce Filtered Image of Monalisa

The following code demonstrates how to perform image filtering in the frequency domain using Fast 
Fourier Transform (FFT) in Python with OpenCV and NumPy libraries. 
1. Performing FFT: The grayscale image is transformed into the frequency domain using FFT. This is 
done using NumPy's ‘np. . 2()’ func on to compute the 2-dimensional FFT, followed by 
‘np. . shi ()’ to shi the zero frequency component to the center, and compu ng the magnitude 
spectrum using ‘np.abs()’ and logarithmic transforma on for be er visualiza on. 
2. Applying Gaussian Blur Filter: The code applies a Gaussian blur filter in the frequency domain. It is 
done by crea ng a mask, centering it and applying it to the  image.   
3. Visualizing the Filtered FFT Image: The magnitude spectrum of the filtered FFT image is computed 
using logarithmic transforma on for be er visualiza on. The resul ng image is then displayed using 
‘matplotlib.pyplot.imshow()’. 
3. Inverse of the Filtered FFT Image: The magnitude spectrum of the filtered FFT image is inversed 
using ‘np.fft.ifft2()’ and the result is displayed.

Some other standard filters are also used.
