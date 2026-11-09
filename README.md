# USRP FPV Video Receiver

Experimental analog FM FPV video receiver using USRP B210 and GNU Radio.

## Requirements
- USRP B210 with a suitable receive antenna
- USB 3.0 connection
- GNU Radio Companion and UHD

## Usage
Open phase_difference.grc in GNU Radio Companion.
Set the device serial number, center frequency and sample rate for your setup.
Generate and run the flowgraph.

## Status
Includes FM demodulation, spectrum monitoring and grayscale video display.
Automatic horizontal and vertical synchronization is not yet implemented.
# usrp-fpv-video-receiver
