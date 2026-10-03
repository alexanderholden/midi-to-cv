# MIDI to CV converter
This is a project that will allow me to read MIDI commands from my computer and then play my analogue synthesisers with it.

This is the first version and it features a 1V/Oct output and a gate output.

##Future upgrades:
- More features (CC and velocity for example)
- Upgrade to USB-C
- Redesign PCB to be more efficient and not require an entire Raspberry Pi Pico

##Current status:
- PCB ordered
- Custom firmware in development


##Rendering:

<img width="895" height="771" alt="image" src="https://github.com/user-attachments/assets/33dac1d6-ee4b-4827-8793-183fe08810be" />

##Schematic:

<img width="3508" height="2480" alt="image" src="https://github.com/user-attachments/assets/f770e7d4-2494-4916-92e4-6ae096426ba3" />

##Parts list:

- Raspberry Pi Pico 2020
- MCP4725 12-bit DAC
- 2x 2K resistors
- 3x 10K resistors
- Polulu 5V step up converter
- 2x 1/4 audio jack


##Sources:

- MCP4725 breakout board schematic: https://learn.adafruit.com/mcp4725-12-bit-dac-tutorial/download
- QtPy MIDI to CV Skull: https://learn.adafruit.com/circuitpython-midi-to-cv-skull
- MIDI info: https://www.instructables.com/Send-and-Receive-MIDI-with-Arduino/
- Arduino MIDI to CV: https://www.instructables.com/Another-MIDI-to-CV-Box-/
