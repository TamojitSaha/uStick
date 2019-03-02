# uStick
μStick (pronounced as "mu stick")or uStick is a 32bit Arm Cortex M0+ based Arduino Compatible micro development board specially designed for battery driven projects/products.
The project is available to order from [OSH Park](https://oshpark.com/projects/SfXMe0NL).

## Features:
- Micro Dev Board (39mm x 15mm)
- ATSAMD11C14 -- 32bit Arm Cortex M0+ 
- 16kb flash, 4kb SRAM
- Battery charging modes(user configurable): 
	- 1. USB 100mA
	- 2. USB 500mA
	- 3. Resistor settable charging current upto 1.6A
- Low noise LDO
  - low Output-VoltageNoise:12 μVRMSTypical
  - PSRRat 1 kHz:75 dB Typical
  - OutputVoltageTolerance(VOUT≥3.3 V): ±2%
  - Low IQ(Enabled,No Load):30 μA Typical
  - Low Dropout(VOUT≥3.3 V): 95 mV Typical at 500 mA Load
- Choosable EEPROM(16-512 MegaBit, refer to [this](https://github.com/Marzogh/SPIMemory) library)
- Auto charging and system power management
- Charging status and power good indicator
- Button configurable for reset or general use (pin D15) with debouncing.
  -  Use as reset (default), with bootloader entry via reset double-tap
  - Use as a general purpose button, with bootloader entry by holding during powerup.
- ESD protection on USB D+ and D- lines
- 9 solder jumpers on PCB bottom for configuration flexibility
- Arduino compatible (use the Arduino IDE to upload)

## Design Layout

<img src="https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/d2f6fcf82c3233004c6eeb3521fc9b59.png"
height="150px">&nbsp;&nbsp;<img src= "https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/7b0fc63ea3109b00a3c7d600d40abf2c.png" height="150px">

## License
The source files are released under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-sa.png" height = "31px">
