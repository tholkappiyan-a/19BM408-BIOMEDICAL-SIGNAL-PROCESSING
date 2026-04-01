# DESIGN OF DIGITAL BUTTERWORTH LOW PASS FILTER USING BILINEAR TRANSFORMATION
# Aim:

To design a digital Butterworth low pass filter using the bilinear transformation method in MATLAB satisfying the given constraints:

0.707≤∣H(ω)∣≤1.0;0≤ω≤0.2π

∣H(ω)∣≤0.08;0.4π≤ω≤π

Assume sampling period T=1second.

# APPARATUS REQUIRED :
MATLAB software
Computer system

Given Specifications

Passband edge frequency:

ω_p=0.2π

Stopband edge frequency:

ω_s=0.4π

Passband ripple:

A_p=-20〖log⁡〗_10 (0.707)=3" dB"

Stopband attenuation:

A_s=-20〖log⁡〗_10 (0.08)≈21.94" dB"

Sampling period:

T=1" second"

# THEORY :
The Butterworth filter is a maximally flat magnitude filter with no ripples in the passband and stopband.
The bilinear transformation converts an analog filter into a digital filter using the relation:

s=2/T  (1-z^(-1))/(1+z^(-1) )

Frequency pre-warping is done to compensate for frequency distortion introduced by bilinear transformation.
The steps involved are:

1)Prewarp digital frequencies to analog frequencies.  

2)Design analog Butterworth filter.
  
3)Convert analog filter into digital filter using bilinear transformation.
  
4)Plot magnitude and phase response.

# ALGORITHM :

1.	Specify passband and stopband edge frequencies.
2.	Convert digital frequencies to analog frequencies using pre-warping.
3.	Compute filter order and cutoff frequency using Butterworth approximation.
4.	Design analog Butterworth low pass filter.
5.	Convert analog filter into digital filter using bilinear transformation.
6.	Plot frequency response using freqz.
7.	Verify whether the filter satisfies the given constraints.

# MATLAB CODE :

<img width="451" height="680" alt="Screenshot 2026-03-31 152030" src="https://github.com/user-attachments/assets/b2f8c3be-e579-4adb-9fa2-3b9469fd907a" />
<img width="380" height="380" alt="image" src="https://github.com/user-attachments/assets/45585181-c907-4f94-9544-f83e32161220" />


# OUTPUT GRAPH :

<img width="822" height="545" alt="image" src="https://github.com/user-attachments/assets/d1f65464-517a-463e-b4b7-343dd582084a" />
<img width="811" height="546" alt="image" src="https://github.com/user-attachments/assets/a4918f8b-652a-400c-a2c6-df9cadcc52af" />


# RESULT:
A digital Butterworth low pass filter satisfying the given constraints was successfully designed using the bilinear transformation method and its frequency response was verified using MATLAB.


