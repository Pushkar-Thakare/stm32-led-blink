# STM32 Two LED Blink Project

Simple microcontroller project to blink onboard LED.

## Hardware
- **Board**: STM32 Blue Pill
- **Programmer**: ST-Link V2
- **MCU**: STM32F103C8T6
- **LEDs**: PC13 (Green)
- **Frequency**: 1Hz (500ms on, 500ms off)

## Quick Start
1. Open `.project` in STM32CubeIDE
2. Build (Ctrl+B)
3. Open Debug folder
4. Open led-blink.elf in STM32CubeProgrammer 
5. Connect ST-Link V2
6. Download the code on STM32 Blue Pill
7. Hit RESET button on the Pill
8. Enjoy!

## Files
- `Core/Src/main.c` - Main application code
- `Core/Inc/main.h` - Header definitions
- `led-blink.ioc` - CubeMX configuration

## Next Steps
- Add button input to control LED patterns
- Add PWM for LED brightness control
- Add multiple leds
