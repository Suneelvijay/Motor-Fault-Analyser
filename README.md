# Motor-Fault-Analyser

ABSTRACT:

Stator current analysis has become a well-established approach for fault detection in induction 
motors, employed in both research and industrial applications. This project presents the results of a 
hardware-based study using current signal analysis to detect bearing faults in a three-phase induction 
motor at 60% and 70% of full load. We propose a novel diagnostic method that combines established 
techniques such as Fast Fourier Transform (FFT) and Short-Time Fourier Transform (STFT) with the less 
commonly used Impulse Invariant Response (IIR) technique. Current signal data is acquired using ACS712 
current sensor, a PIC microcontroller and processed in MATLAB to extract dominant frequency 
components. These are then compared to those of a healthy motor to identify and analyze potential faults. 
Additionally, the study incorporates statistical measures such as mean, variance, and kurtosis for a 
comprehensive analysis. Our findings, based on tests at different load levels, demonstrate the effectiveness 
of these techniques in early detection of bearing faults. Future work aims to refine these methods and 
explore their application in diverse real-time industrial settings, potentially revolutionizing maintenance 
approaches by preventing machinery breakdowns and optimizing operational efficiency.

KEYWORDS: Three Phase Induction motors, Fast Fourier transform, Infinite Impulse Response, Shorttime Fourier transform, , Fault Detection, Bearing fault

Website Link:
https://motorfaultanalyser.netlify.app/

APP LINK:
https://drive.google.com/file/d/1rHF7O7k_O-Nkvys4gasZxh4hvMTtbNbw/view?usp=drive_link

Guidelines for using the app:
1. Download the MATLAB application from the provided drive link.
2. Collect Healthy and Input motor current signals in CSV file format.
3. Ensure that all these files are present in same directory.
