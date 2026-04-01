# DESIGN OF DIGITAL CHEBYSHEV LOW PASS FILTER USING BILINEAR TRANSFORMATION

# AIM:
To design a digital Chebyshev low pass filter using the bilinear transformation method in MATLAB satisfying the following constraints:

0.8≤∣H(ω)∣≤1.0;0≤ω≤0.2π

∣H(ω)∣≤0.2;0.32π≤ω≤π
Assume sampling period T=1second.

# APPARATUS REQUIRED :

MATLAB software
  
Computer system
  
Given Specifications

Passband edge frequency:

ω_p=0.2π

Stopband edge frequency:

ω_s=0.32π

Passband ripple:

A_p=-20〖log⁡〗_10 (0.8)≈1.94" dB"

Stopband attenuation:

A_s=-20〖log⁡〗_10 (0.2)≈13.98" dB"

Sampling period:

T=1" second"

# Theory:

Chebyshev filters provide a sharper transition between passband and stopband compared to Butterworth filters but allow ripples in the passband (Type-I).
The bilinear transformation converts an analog filter into a digital filter using:

s=2/T  (1-z^(-1))/(1+z^(-1) )

Frequency pre-warping is required to compensate for frequency warping introduced by bilinear transformation.
Steps involved:
Prewarp the digital frequencies.
Design an analog Chebyshev filter.
Convert it into a digital filter using bilinear transformation.
Plot magnitude and phase response.

# ALGORITHM :

1)Specify passband and stopband edge frequencies.

2)Convert digital frequencies into analog frequencies using pre-warping.

3)Calculate filter order using Chebyshev approximation.

4)Design analog Chebyshev low pass filter.

5)Convert analog filter to digital filter using bilinear transformation.

6)Plot frequency response using freqz.

7)Verify that the designed filter meets the given constraints.

# MATLAB CODE :

<img width="481" height="691" alt="image" src="https://github.com/user-attachments/assets/45fc56c5-22f3-4776-a67d-0aa1f7567702" />
<img width="446" height="390" alt="image" src="https://github.com/user-attachments/assets/cd64e361-f212-41a8-b140-4b2c0b3a033d" />


# OUTPUT GRAPH :

<img width="808" height="549" alt="Screenshot 2026-03-31 152417" src="https://github.com/user-attachments/assets/bd4e66f4-2d63-4658-bd9b-a676e6ef3fc8" />
<img width="812" height="558" alt="Screenshot 2026-03-31 152425" src="https://github.com/user-attachments/assets/813f5c53-830f-4cf7-85b8-9f2f75225838" />

# RESULT:
A digital Chebyshev low pass filter satisfying the given specifications was successfully designed using the bilinear transformation method and its frequency response was verified using MATLAB.
