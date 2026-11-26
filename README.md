# Water Tank Level Monitoring and Simulation

**Process Control · Simulink · MATLAB UI**

A tank-level modeling project with a MATLAB monitoring interface and a Simulink model.

```mermaid
flowchart LR
 A[Simulated level] --> B{Level at or below 5 cm?}
 B -->|Yes| C[Pump ON]
 B -->|No| D[Pump OFF]
 C --> E[MATLAB interface]
 D --> E
```

## Engineering highlights

- Simulink model of the water pump system.
- MATLAB app with start/stop monitoring and a one-second timer.
- Simulated level readings of 0–10 cm; pump ON at or below 5 cm.

## Project files

| File | Purpose |
| --- | --- |
| [Project Report.pdf](Project%20Report.pdf) | Original source or design file |
| [WaterLevelTank.mp4](WaterLevelTank.mp4) | Original source or design file |
| [WaterPump.slx](WaterPump.slx) | Original source or design file |
| [WaterPumpApp.m.txt](WaterPumpApp.m.txt) | Original source or design file |

## How to explore or reproduce

Open `WaterPump.slx` in MATLAB/Simulink. To try the separate monitoring interface, copy `WaterPumpApp.m.txt` to `WaterPumpApp.m` in a MATLAB working directory and execute `app = WaterPumpApp;`. Review the report and video for context.

## Scope and limitations

The UI generates random readings and is not connected to a physical sensor or the Simulink model. The simulation has not been rerun during this documentation update.

## Portfolio

[Hassan Ali Janjua — Engineering portfolio](https://github.com/HassanAliJanjua03)
