# Delta Klipper Configuration

These configuration files are for my own extremely modified AnyCubic Kossel Linear Plus.
⚠️ _THESE WILL NOT WORK FOR THE STOCK MODEL AND WILL DAMAGE A STANDARD MACHINE!_ 🚧

Configurations are provided as-is as they are solely for my own personal use, but have been uploaded to a public repository for anyone to use as reference.

Please follow the [official Klipper documentation](https://www.klipper3d.org/) whenever configuring your own machine.

t;lr I can't be held responsible if you break your own machine.

---

## Hardware Notes

In no particular order, here are some notes about the upgraded hardware to my specific machine. I've listed these so that people may reference them easier if using the same components.

### Print orientation

My own machine is fitted to work inverted (upside-down. Inspired by the [Positron printer](https://www.youtube.com/watch?v=ZAPaOevoeX0)).
Stepper motor configs have been set to make this possible, by inverting the A & B (X+Y axis) towers & the motor dir/enable pins. This is _one_ of the reasons that this configuration would damage a standard model.

### Effector

This configuration is for a [Duet Smart Effector](https://www.duet3d.com/DeltaSmartEffector). The probe offset & pin configuration (which was a fucking nightmare, thanks for that @Duet3D. Never again.) should (again) be only used as reference.

### Extruder

Configs are for an [Orbiter 2.0](https://orbiterprojects.com/orbiter-v2-0/). Your retraction rate, pressure advance,

### Resonance Compentation

The effector is mounted with an ADXL345 wired directly to the SKR 1.4T MCU for resonance compensation.

### Main Control Unit

Configs are set for a SKR 1.4 Turbo wiring layout with TMC2209 stepper drivers & sensorless homing.
[Why? because my Kossel's original Trigorilla board was damaged due to me being a twat. Use terminal housings+heatshrink & don't short your boards, people. Only you can prevent hardware fires.]
