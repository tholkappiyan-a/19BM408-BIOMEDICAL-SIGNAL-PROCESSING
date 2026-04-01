# HAMMING WINDOW BASED FIR FILTER DESIGN
# AIM :
To design a Low Pass FIR filter using Hamming Window and study its frequency characteristics.
# THEORY:

Hamming window is defined as:

w(n)=0.54-0.46cos⁡(2πn/N)

Characteristics:
Reduced side lobes

Better stopband attenuation (~41 dB)

Slightly wider main lobe than rectangular

Reduced ripple

Design Equation:

h(n)=h_d (n)⋅w(n)

Where hd(n) is ideal impulse response.

# ALGORITHM:
1.	Choose N and ωc
2.	Compute ideal impulse response
3.	Generate Hamming window
4.	Multiply and obtain h(n)
5.	Plot magnitude & phase

# MATLAB CODE :

<img width="323" height="288" alt="image" src="https://github.com/user-attachments/assets/6c266bcd-8d6f-44cc-8de9-841529a657e7" />

# OUTPUT GRAPH :

<img width="822" height="544" alt="image" src="https://github.com/user-attachments/assets/13bc8928-4eaa-4c6f-9c5b-29d89fb3ecac" />

# RESULT :
The FIR filter was designed using Hamming window .
