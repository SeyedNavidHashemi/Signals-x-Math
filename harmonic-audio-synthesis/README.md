# Harmonic Audio Synthesis and Fourier Analysis

A Signals and Systems project that demonstrates digital audio synthesis and frequency domain analysis through music generation and note recognition.

## Overview

This project implements a complete audio synthesis pipeline that generates musical melodies using pure sine waves, analyzes real instrument recordings through Fourier Transform, and reconstructs music using harmonic overtones. The implementation includes:

- **Signal Generation**: Creating musical notes from fundamental frequencies
- **FFT Analysis**: Extracting harmonic coefficients from recorded audio files
- **Audio Reconstruction**: Synthesizing realistic-sounding notes using multiple harmonics
- **Note Recognition**: Automatic identification of musical notes from audio signals

## Key Features

- Synthetic audio generation using pure sinusoidal waves
- Frequency domain analysis using Fast Fourier Transform (FFT)
- Harmonic coefficient extraction and storage
- Damped harmonic synthesis for realistic audio timbre
- Peak detection and note identification algorithms
- Visualization of frequency spectrums for musical analysis

## Technical Implementation

The project employs signal processing techniques including:

- **Sampling Theory**: 44.1 kHz sampling rate for high-quality audio reproduction
- **Discrete Fourier Transform**: Frequency domain conversion for harmonic analysis
- **Peak Detection**: Signal analysis for note onset and duration estimation
- **Envelope Modulation**: Exponential decay functions for natural note decay

## Technologies Used

- Python (NumPy, SciPy)
- Jupyter Notebook
- Digital Signal Processing
- Fourier Analysis
- Audio Processing

## Results

Successfully generated and optimized the "Harry Potter Theme" melody, demonstrating the transformation from basic sine wave synthesis to harmonic-enriched audio that closely mimics real instrument timbre.

