# Wiring guide

This is a low-voltage prototype wiring plan for **Vertical Farm Controller Camera Growth Tracking**. Confirm every module's datasheet because breakout-board pinouts vary.

| Component | Suggested pin | Role | Check |
| --- | --- | --- | --- |
| load cell | A0 | Analog input | Confirm the module voltage and pinout before power-up. |
| pH sensor | A1 | Analog input | Confirm the module voltage and pinout before power-up. |
| solar charger | 4 | Digital I/O | Confirm the module voltage and pinout before power-up. |
| Status output | LED_BUILTIN | Output | Use a resistor when an external LED is fitted. |

## Power

- Use a regulated supply sized for the selected modules.
- Join grounds unless an interface is explicitly isolated.
- Do not connect mains voltage directly to a development board.
- Add a fuse, emergency stop, and certified isolation where a real actuator can create risk.
