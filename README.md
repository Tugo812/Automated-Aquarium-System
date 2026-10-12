# Automated-Aquarium-System
- Built an Arduino system that monitors water temperature, flow, and level. It automatically controls a mains-powered heater (through a relay), a water pump, LED day/night lighting, and a 3D-printed fish feeder
- Wrote the control program in C++. It uses non-blocking timers so every task runs at the same time, hysteresis so the heater relay doesn’t switch on and off too fast, and a settings profile for each of two fish species that can be switched
- Tested the system dry and in water, logged 30 minutes of sensor data and plotted it in MATLAB. Found that the level sensor was unreliable, and recalibrated the feeder after its servo had to be swapped for a different type
- Total cost about $150, compared with $660–990 for commercial controllers
- Uses my old in the report
