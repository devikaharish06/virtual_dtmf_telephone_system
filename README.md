# virtual_dtmf_telephone_system
“Virtual DTMF Telephone System using Digital Signal Processing and FFT in Python
# Virtual DTMF Telephone System Using Digital Signal Processing

## Project Overview

This project implements a software-based Virtual DTMF Telephone System using Python and Digital Signal Processing techniques.

DTMF (Dual-Tone Multi-Frequency) is a signaling technique used in telephone systems where each keypad key is represented by a combination of two frequencies.

In this project, a virtual telephone keypad is created using Python. When a key is pressed, the corresponding DTMF signal is generated. FFT (Fast Fourier Transform) is then used to detect the frequency components and decode the corresponding digit.

## Features

* Virtual telephone keypad
* DTMF signal generation
* FFT-based frequency detection
* Complete number decoding
* Time-domain waveform visualization
* FFT frequency spectrum
* DTMF audio output
* No external hardware required

## DTMF Frequencies

| Key | Low Frequency | High Frequency |
| --- | ------------: | -------------: |
| 1   |        697 Hz |        1209 Hz |
| 2   |        697 Hz |        1336 Hz |
| 3   |        697 Hz |        1477 Hz |
| 4   |        770 Hz |        1209 Hz |
| 5   |        770 Hz |        1336 Hz |
| 6   |        770 Hz |        1477 Hz |
| 7   |        852 Hz |        1209 Hz |
| 8   |        852 Hz |        1336 Hz |
| 9   |        852 Hz |        1477 Hz |
| *   |        941 Hz |        1209 Hz |
| 0   |        941 Hz |        1336 Hz |
| #   |        941 Hz |        1477 Hz |

## Technologies Used

* Python
* Google Colab
* NumPy
* Matplotlib
* IPyWidgets
* IPython

## Working Principle

**Virtual Keypad → DTMF Signal Generation → Sampling → FFT → Frequency Detection → DTMF Table Matching → Decoded Digit**

The sampling frequency used in the project is **8000 Hz**.

## Project Objective

The main objective is to demonstrate the practical application of Digital Signal Processing concepts such as signal generation, sampling, FFT, frequency-domain analysis and signal decoding.

## Applications

* Telephone systems
* IVR systems
* Automated customer service
* Home automation
* Remote-control systems
* Telecommunication systems

## Future Scope

* Real-time DTMF detection
* Microphone-based input
* Noise filtering
* Detection from recorded audio
* Real telephone-line signal processing
* Standalone GUI application
