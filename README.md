# Artix 7 based ultrasound microphone Adapter 

This is a small farewell project to my [Ultrasound Microphone Array Adapter](https://github.com/myildirim6198/UltrasoundMicrophoneArrayAdapterBAT) thesis project. To support a higher frequency bandwidth with high dynamic range an fpga is used.

# Hardware features

- FPGA: XC7A100T-2CSG324I
- External memory: 125 MByte DDR2 RAM, 16 MByte QSPI Flash
- Digital Connections: 1x USB-C for programming and debugging, 1x USB-C up to 480 MBit/s for transfering data
- ADC: TAA3020 2 Channel Audio-ADC up to 768 kHz sampling Frequency
- Pre-amplifier stage: 36 dB
- Microphones: 2x STMicroelectronics IMP23ABSUTR 2.2 mm gap to each other

# Applications:

- Microphone Arrays
- Ultrasound
- Bat detection and localisation

# Absolute Maximum Ratings

- Supply Voltage: +5V0 to +5V5 (recommended: +5V0) USB feeded

# Manufacturing Information

- Length = 50mm, Width = 50mm, Thickness = 1.2 mm
- Layers = 8
- Min. Via Hole diameter = 0.3 mm
- Via-Type: Epoxy Filled and Capped
- Impedance Control: JLC08121H-3313
- Surface Finish: ENIG
- Material Type: FR-4 TG155


# Progress

- Schematic design: complete
- Layouting: complete
- Manufacturing & assembly: In progress
- Bring-Up: In progress

I make no guarantees as to device funtionality. Please review the components, schematics carefully before production.
