# AVR / Arduino Toolchain

## Command Line Tools

Using [ladislas/Bare-Arduino-Project](https://github.com/ladislas/Bare-Arduino-Project):

1. Install Homebrew and Git
1. Install the [Arduino IDE](https://www.arduino.cc/en/main/software)
1. Install the AVR command line tools:
```
brew tap osx-cross/avr
brew install avr-gcc
brew install avrdude
```
   
### Others

**[Arduino CLI][arduino-cli]**

[arduion-cli]: <>

**[CrossPack AVR][crosspack]**

Old (last updated in 2013, using GCC 4), but "normal" command line toolchain.

```brew cask install crosspack-avr```

[crosspack]: <>
