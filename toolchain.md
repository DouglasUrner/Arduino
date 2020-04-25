# AVR / Arduino Toolchain

## Command Line Tools

The Bare Arduino Project repository builds on [Arduino Makefile]().

Using [ladislas/Bare-Arduino-Project](https://github.com/ladislas/Bare-Arduino-Project):

Toolchain install:
1. Install Homebrew and Git
1. Install the [Arduino IDE](https://www.arduino.cc/en/main/software)
1. Install the AVR command line tools:
   ```bash
   brew tap osx-cross/avr
   brew install avr-gcc
   brew install avrdude
   ```
1. Install the `pySerial` library:
   ```
   pip3 install pyserial
   ```
Once the toolchain is installed:
1. Clone the Bare-Arduino-Project repository.

### Others

**[Arduino CLI][arduino-cli]**

[arduion-cli]: <>

**[CrossPack AVR][crosspack]**

Old (last updated in 2013, using GCC 4), but "normal" command line toolchain.

```brew cask install crosspack-avr```

[crosspack]: <>
