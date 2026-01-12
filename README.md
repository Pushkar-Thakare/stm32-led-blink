# STM32 Two LED Blink Project

Simple microcontroller project to blink onboard LED.

## Hardware
- **Board**: STM32 Blue Pill
- **MCU**: STM32F103C8T6
- **LEDs**: PC13 (Green)
- **Frequency**: 1Hz (500ms on, 500ms off)

## Quick Start
1. Open `led-blink.ioc` in STM32CubeMX
2. Click "Generate Code"
3. Open project in STM32CubeIDE
4. Build (Ctrl+B) and Run (F11)

## Files
- `Core/Src/main.c` - Main application code
- `Core/Inc/main.h` - Header definitions
- `led-blink.ioc` - CubeMX configuration

## Next Steps
- Add button input to control LED patterns
- Add PWM for LED brightness control
- Add multiple leds
