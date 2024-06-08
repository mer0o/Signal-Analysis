
# Signal Analysis Project - Comm B301 - German International University

## Project Overview

This project is part of the Signals and System Theory course (Comm B301) in the Communications Engineering program. The goal of this project is to analyze and manipulate audio signals using various signal processing techniques including plotting, scaling, shifting, Fourier Transform, frequency shifting, and applying low-pass filters.

## Project Structure

### 1. Setup

#### 1.1 Importing Libraries
The project utilizes the following Python libraries:
- `numpy`: For numerical operations.
- `matplotlib`: For plotting graphs.
- `scipy.io.wavfile`: For reading WAV files.
- `math.ceil`: For rounding up values.
- `IPython.display`: For displaying audio.

#### 1.2 Loading Recordings
Three audio recordings (`mero.wav`, `Hamza.wav`, and `Abyad.wav`) are loaded. The sample rate and dimensions of the signals are inspected.

### 2. Plotting the Original Signals
The original signals are plotted against time to visualize the waveforms.

### 3. Shifting and Scaling

#### 3.1 Function Definition
A function `scale_and_shift` is defined to scale and shift signals based on provided parameters.

#### 3.2 Applying the Function
The scaling and shifting function is applied to the recordings, and the results are plotted.

#### 3.3 Combining Signals
Functions are defined to extend signals to the same length and to combine original and edited signals. The combined signals are plotted and played to compare the effects.

### 4. Fourier Transform & Frequency Shifting

#### 4.1 Fourier Transform
The Fast Fourier Transform (FFT) is performed on the signals to convert them from the time domain to the frequency domain.

#### 4.2 Frequency Shifting
The frequencies of the signals are shifted, and the inverse FFT is applied to obtain the time-domain signals with shifted frequencies. The effects of frequency shifting are plotted and played.

### 5. Low Pass Filter

#### 5.1 Function Definition
A low-pass filter function is defined to filter out frequencies above a specified cutoff frequency.

#### 5.2 Applying the Filter
The low-pass filter is applied to the signals.

#### 5.3 Plotting
The signals are plotted in both time and frequency domains before and after applying the low-pass filter.

## Running the Code
1. Ensure you have the required libraries installed:
   ```bash
   pip install numpy matplotlib scipy ipython
   ```
2. Place the audio recordings (`mero.wav`, `Hamza.wav`, `Abyad.wav`) in a folder named `Recordings`.
3. Run the code in a Python environment that supports Jupyter notebooks or directly execute the Python script.

## Conclusion
This project demonstrates the application of fundamental signal processing techniques on audio recordings. It provides a comprehensive understanding of signal manipulation, including time and frequency domain transformations, and the practical implementation of signal filters.

For further information or questions, please contact me with an issue.

---

By following the structure and instructions provided in this README, you should be able to understand the signal processing techniques I applied in this project. Happy *"signalysis"*!
