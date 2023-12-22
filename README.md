Signal Source Separation using Classical ML Techniques with SNR as Performance Metric

Abstract

Signal and source separation is a crucial task in audio processing, speech recognition, and music analysis. This project employs exploratory data analysis (EDA) techniques along with various machine learning algorithms to separate signal and sources in audio files. Techniques such as Short-Time Fourier Transform (STFT) are used to compute spectrograms, providing a time-frequency representation of the signal. EDA is then applied to extract crucial features, including RMS energy, Zero Crossing Rate, MFCCs, Chroma, and Tempogram, from the spectrogram. The study explores algorithms like REPET, FastICA, ButterworthFilter, NMF, HarmonicPercussion, and GaussianNMF for signal and source separation.

Methodology

The study utilizes FastICA, REPET, NMF, Gaussian NMF, Harmonic Percussion, and Butterworth filter to perform signal source separation. The focus is on achieving optimal accuracy metrics, especially Signal-to-Noise Ratio (SNR). Rigorous optimization is applied to fine-tune the algorithms for superior performance in audio signal separation.

Results

The implementation of FastICA combined with the Harmonic Percussion method yields an impressive SNR of 20+ in testing data, even in the presence of highly negative noise and distortions. The study showcases the effectiveness of REPET, FastICA, ButterworthFilter, NMF, HarmonicPercussion, and GaussianNMF in separating sources from complex audio mixtures.

Insights from EDA Analysis

Exploratory Data Analysis (EDA) is performed on audio parameters such as channels, sample width, frame rate, intensity, and derivative parameters like spectrogram, RMS energy, Zero Crossing Rate, Spectral Centroid, MFCCs, Chromagram, and Tempogram. These analyses provide valuable insights into the characteristics of the audio signals.

Inferences from Algorithmic Approaches

REPET:
Precision in Source Separation
Adaptability to Various Audio Types
Robustness to Noise
Computational Efficiency
NMF:
Effective Source Separation
Versatility Across Audio Types
Resilience to Noise
Computational Efficiency
Gaussian NMF:
Effective Signal Decomposition
Adaptability to Audio Types
Noise Tolerance
Efficient Processing
Harmonic Percussions:
Harmonic Component Isolation
Enhanced Music Analysis
Useful in Various Genres
Resilience to Noise
FastICA:
Efficient Signal Separation
Versatile Application
Noise Resilience
Real-Time Processing Capability
Conclusions

The optimization of algorithms leads to robust models for separating signals and sources. Each algorithm exhibits strengths in specific areas, and their combination can provide comprehensive solutions. The Signal-to-Noise Ratio (SNR) metrics indicate the effectiveness of the implemented techniques, with the FastICA and Harmonic Percussion method achieving an outstanding SNR of 20+ in testing data. These results contribute significantly to advancements in audio processing and signal source separation.
