# lufarduino
Build LUFA-powered programs with the familiar Arduino IDE

### Only tested on Linux!

#### Installation:

Download either a release file, or clone it with

`git clone https://github.com/nullstalgia/lufarduino --recursive`

Copy `lufarduino` into `/usr/share/arduino/hardware/`

Make sure you copy the right folder!

If you did it right, it should be like this:

```
$> pwd
/usr/share/arduino/hardware/lufarduino/avr/
```

Notes: 

`Serial1` (Hardware UART) has been aliased to `Serial` to allow for certain libraries to compile without breaking.

Thanks to:

[Palatis for Arduino-Lufa](https://github.com/Palatis/Arduino-Lufa)

[Dean Camera for LUFA](https://github.com/abcminiuser/lufa)
