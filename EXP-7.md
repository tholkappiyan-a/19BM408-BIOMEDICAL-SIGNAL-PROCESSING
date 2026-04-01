# RECTANGULAR WINDOW BASED FIR FILTER DESIGN
# AIM :
To design a Low Pass FIR filter using Rectangular Window and analyze its magnitude and phase response using MATLAB.
# Theory :
Rectangular Window
The Rectangular window is defined as:
        w(n)=1≤n≤N
Characteristics:
Narrowest main lobe

Highest side lobes

High ripple (Gibbs phenomenon)

Sharp transition width

It simply truncates the ideal impulse response.

Design Equations
Ideal Low Pass Impulse Response:

h_d (n)=(sin⁡ω_c (n-α))/(π(n-α))

Where:

α=N/2

Actual filter:

h(n)=h_d (n)⋅w(n)

# ALGORITHM :
1.	Choose filter order N
2.	Choose cutoff frequency ωc
3.	Generate ideal impulse response
4.	Generate rectangular window
5.	Multiply both
6.	Plot frequency response

# MATLAB CODE :

<img width="593" height="604" alt="image" src="https://github.com/user-attachments/assets/da095475-44a6-4cf8-aaf5-57649a508864" />

# OUTPUT GRAPH :

<img width="852" height="542" alt="image" src="https://github.com/user-attachments/assets/7999a078-5a0b-4868-8166-da358e461c9f" />

# RESULT :
The FIR filter was designed using Rectangular window.
