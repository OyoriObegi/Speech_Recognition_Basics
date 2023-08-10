# Speech_Recognition_Basics
This repository contains Python scripts that demonstrate basic audio processing tasks using the `wave` module and how to read and plot a WAV audio signal using the `matplotlib` and `numpy` libraries.

## Audio Processing Basics 

1. Open a WAV file using the `wave` module.
2. Print information about the WAV file, including number of channels, sample width, frame rate, number of frames, and parameters.
3. Calculate the duration of the audio in seconds.
4. Read audio frames and write them to a new WAV file with different parameters.

## Plotting WAV Signal 

Reads a WAV audio file, extracts the audio signal, and plots the signal over time:

1. Open a WAV file using the `wave` module.
2. Calculate the sample frequency and number of samples.
3. Read the audio frames and convert them to an array of int16 values.
4. Generate time values for plotting based on the duration of the audio.
5. Plot the audio signal against time using `matplotlib`.

## Getting Started

1. Clone the repository to your local machine using `git clone https://github.com/OyoriObegi/Speech_Recognition_Basics.git`
2. Make sure you have Python and the required libraries (`matplotlib`, `numpy`, `wave`) installed.



## Acknowledgments

- The code examples are inspired by *freecodecamp* YouTube tutorial at https://www.youtube.com/watch?v=mYUyaKmvu6Y&t=1063s  and adapted for educational purposes.
- Thanks to the developers of the `wave`, `matplotlib`, and `numpy` libraries.

Feel free to explore and modify the scripts to suit your needs! If you have any questions or encounter issues, please don't hesitate to open an issue or reach out.
