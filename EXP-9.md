# HANNING WINDOW BASED FIR FILTER DESIGN

# AIM:

To design a Low Pass FIR filter using Hanning (Hann) Window and analyze its response.
# THEORY :

Hanning window is defined as:

w(n)=0.5-0.5cos⁡(2πn/N)

Characteristics:

1)Smooth tapering at ends

2)Reduced spectral leakage

3)Moderate stopband attenuation (~31 dB)

4)Wider main lobe than Hamming

Design Equation:

h(n)=h_d (n)⋅w(n)

# ALGORITHM :
1.	Select N and ωc
2.	Compute ideal response
3.	Generate Hanning window
4.	Multiply and obtain FIR coefficients
5.	Plot response

# MATLAB CODE :

<img width="315" height="282" alt="image" src="https://github.com/user-attachments/assets/db8200d2-1ad6-431a-9762-6cde5d875a15" />

# OUTPUT GRAPH :

<img width="821" height="541" alt="image" src="https://github.com/user-attachments/assets/af591fde-5f06-4f53-b7df-6ba09181623b" />

# RESULT :
The FIR filter was designed using Hanning window.
