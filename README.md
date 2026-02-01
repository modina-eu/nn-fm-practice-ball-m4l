# nn-practice-ball-m4l
Sonification kit for Duophonic Transience research project

# Requirements

## Max/MSP Host

- The patch can run as a standalone app or as a device in Ableton Live via Max4Live. The external libraries (listed below) must be installed to the correct file path.
- Max/MSP standalone - [https://cycling74.com/products/max-9](url)
- Max4Live - https://www.ableton.com/en/live/max-for-live/

## External Libraries and models

### RAVE/nn~ for audio

nn-tilde for RAVE - [https://github.com/acids-ircam/nn_tilde/releases/](url)

See README instructions for installation on Windows or MacOS

- This patch was developed with nn~ v1.6
- Download the water_pondbrain model by Intelligent Instruments Lab - [https://huggingface.co/Intelligent-Instruments-Lab/rave-models/tree/main](url)
- Pre-trained models must be accessible from the Max file system (Options -> File Preferences)

### DSP

- pipo - [https://github.com/ircam-ismm/pipo](url)
- digital-orchestra-toolbox - [https://github.com/malloch/digital-orchestra-toolbox](url)

### BITalino R-IoT

- This project makes use of the BiTalino R-IoT to acquire and stream IMU and sensor data. With some tinkering inside the patch, this can be replaced with an alternative sensor device or just the microphone input.
- motion analysis max objects - [https://github.com/Ircam-R-IoT/motion-analysis-max](url)
- We are using the latest max-bitalino-riot2
