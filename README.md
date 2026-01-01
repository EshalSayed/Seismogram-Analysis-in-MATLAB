**Seismogram Analysis using MATLAB**

Analysis and Operations on a Real-World Earthquake Signal

Overview :

This project presents the analysis of a real-time seismogram signal recorded during the 2011 Tōhoku (Japan) earthquake.
The objective is to apply fundamental Signals and Systems concepts to real seismic data using MATLAB, enabling both time-domain and frequency-domain analysis.
The work demonstrates how theoretical signal processing techniques can be effectively applied to real-world geophysical data for earthquake interpretation and analysis.

Objectives :

Analyze a real earthquake seismogram signal
Perform basic time-domain signal operations:
Time Delay
Time Reversal
Time Scaling
Compute the energy and power of the signal
Apply Fourier Transform to obtain:
Magnitude Spectrum
Phase Spectrum
Understand the relevance of signal operations in earthquake monitoring and interpretation

Dataset :
Event: 2011 Japan (Tōhoku) Earthquake
Source: IRIS (Incorporated Research Institutions for Seismology)
The seismogram was initially obtained as an image and digitized using WebPlotDigitizer
The extracted time–amplitude data was imported into MATLAB as a CSV file

Software Used :
MATLAB (R2025a or compatible versions)
WebPlotDigitizer (for data extraction)

Methodology :
1. Time-Domain Analysis
The original seismogram was analyzed using the following operations:

Time Delay:
The signal was delayed by a fixed duration to study synchronization effects.
Time Reversal:
The signal was reversed along the time axis to observe its behavior when time is inverted.
Time Scaling:
The signal was expanded in time to analyze slower variations and lower-frequency behavior.

2. Energy and Power Computation

Signal energy was calculated using numerical integration (trapezoidal method).
Average power was computed based on the signal duration.
These parameters provide quantitative measures of the earthquake’s recorded intensity.

3. Frequency-Domain Analysis

Fourier Transform was applied to decompose the signal into its frequency components.
The following were obtained:
Magnitude Spectrum
Phase Spectrum
This analysis helps identify dominant frequency components present in seismic ground motion.

Results and Discussion :

Time-domain operations illustrated how seismic signals behave under shifting, reversal, and scaling.
Energy and power calculations quantified the strength of the earthquake vibrations recorded by the sensor.
Fourier analysis revealed dominant low-frequency components typical of seismic waves, which are critical in structural and geotechnical engineering applications.

Applications :

Earthquake monitoring and interpretation
Seismic signal synchronization across sensor networks
Structural and civil engineering design
Vibration and frequency analysis of ground motion
Disaster preparedness and early warning system research

Conclusion :

This project demonstrates the practical application of Signals and Systems concepts to real seismic data. 
By performing time-domain operations, energy and power analysis, and Fourier-based frequency analysis, the project highlights how signal processing techniques 
play a vital role in understanding earthquake behavior and ground motion characteristics.
