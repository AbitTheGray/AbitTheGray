# Projects

This list contains only personal projects.

If the links below do not work, they may be private repositories which I decided to not public (yet).
Not all my projects are listed below, only those I consider mention-worthy.

## Completed

Nothing major yet.

### Small

- [**TP4056 charger**](https://github.com/AbitTheGray/TP4056_Charger) - USB-C 1S LiPo charger with 5V when plugged in and USB D+/- on connector

## In-progress

- [**Roengenium**](https://github.com/AbitTheGray/Roentgenium) (+tutorial) - custom GoldSrc engine implementation, OpenGL
- [**Yautja costume**](https://github.com/AbitTheGray/Yautja) - full Yautja/Predator costume (wireless part communication, animatronics...), ESP32-S3

### Secondary

- **Costume RC Module** - high-frequency LEDs (6), 12V PWM fans (2) and BLE control (maybe even few servo slots)
  - Maybe 2 versions (Basic + Pro) for different sizes
  - **⌀3.5mm 2-color eyes** (for Fursuits, maybe even 3-color version)
- **G-scale train** - ESP32+Battery with optional power from tracks (or overhead line), high-power engine
- [**Voxelite**](https://github.com/voxelite) - Fully customizable "Minecraft clone", server-side modding, custom 3D Vulkan engine

## Postponed

- [**AWEngine**](https://github.com/graymadness/AWEngine) - generic Vulkan 3D engine (cancelled)
- [**IRC**](https://github.com/AbitTheGray/IRC) - IRC protocol implementation (coding practice)

## Planned

### Software

- **Bane** - [DOOM](https://store.steampowered.com/app/2280/DOOM_1993/)/[DOOM2](https://store.steampowered.com/app/2300/DOOM_II/) multiplayer-focused engine/game + map editor
- **Screwdriver** - GoldSrc map editor ([Valve Hammer Editor](https://developer.valvesoftware.com/wiki/Valve_Hammer_Editor) alternative) with LUA (or Python?) plugins

### Hardware

- **Servo Measure** - Tool to test servos and measure current consumption based on its angle
- **LED Fursuit Harness + Collar** - RGB LED indexable strip under white polypropylene webbing, basic controller with remote color/effect controls (build-in microphone for "equalizer" effect)
- **M41A** from Alien franchise (no firing but mechanical feedback)
  - Similar to those seen in [Adam Savage's Tested "Master Chief's Spartan Armor" video](https://www.youtube.com/watch?v=BJVUSldj2SQ)
- [**ESP32 RC receiver**](https://github.com/AbitTheGray/RC_Receiver) (vehicle side) - 16 PWM outputs (50Hz = RC servos) and I2C (QWIIC)
- [**USB PowerDelivery DevKit**](https://github.com/AbitTheGray/USB_PD_DevKit) - ESP32-S3, USB OTG, up to 24V input, Power Delivery sink
- [**USB NumPad**](https://github.com/AbitTheGray/USB_NumPad) - ESP32 NumPad Keyboard (USB-C or Bluetooth)
- **TP4056 multi-charger** - USB-C PowerDelivery for higher voltage, multiple TP4056 each with 1S battery
- **Protogen Fursuit** - Full-display see-through RGB visor
  - Multiple microcontrollers for displays on the body
- PC Peripherals
  - **Keyboard** - ESP32 Full-Size Keyboard (USB-C or Bluetooth)
  - **Mouse** - ESP32 Mouse (USB-C or Bluetooth)
  - **Gamepad** - ESP32 PlayStation-style gamepad (USB-C or Bluetooth)
  - **Headphones** - ESP32 Headphones with volume controls (USB-C or Bluetooth)
- **Upscaled PC Peripherals** - 150% to 200% scale PC peripherals (Mouse, Keyboard, Gamepad)

### Far Future

#### Software

- **KiCad automatic export** - Export BOM, position files (top/bottom for JLCPCB) and Gerber files (usable by Github Actions and output as artifact)
- **???** - Tool for converting maps between game engines (target GoldSrc?)
- **Customizable Android UI App** for BLE devices
- **Roengenium 2** - "Source variant of Roengenium" (different path of GoldSrc evolution, similar to [Source](https://developer.valvesoftware.com/wiki/Source) engine)
- **Dark Souls unifying engine** (back-to-back Dark Souls 1+2+3, support for custom weapons/armor/enemies/bosses)

#### Hardware

- **Arcade Machine**
- **Car Radio** - 1DIN, audio playback (USB / SD Card), BLE controls, Bluetooth speaker (device), WiFi device for internet radio, USB-C PowerDelivery
- USB-C PowerDelivery Hub
  - **Table version** (separated USB-C for power and data)
  - **Front of PC case** (3.5" or 5.25", 8-pin PSU connector and internal USB-C connector)
  - **PCIe** (8-pin PSU connector)
- **USB-C Fan Controller** (using PowerDelivery or DC-DC boost converter for 12V) - potentiometer? temperature sensor? BLE?
- **Laser Tag** with ESP32 (guns and vests) and Raspberry Pi (WiFi AP and game master)
- **Old-school puppet animation rig** - humanoid figure with potentiometers with position feedback
