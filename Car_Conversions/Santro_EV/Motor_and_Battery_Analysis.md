# Motor and Battery Analysis – Santro EV

## Motor Specifications
- Motor: 4000W PMSM (Datai brand) with sine wave controller
- Max power draw: 72V x 72A = 5184 W
- Max RPM: 4200
- Efficient RPM range: 3500–4000
- Front Wheel Drive
- Manual Transmission, 5 gears
- Wheel: 13R (6.5" / 0.1651 m)

### Gear Ratios and Max Speeds
| Gear | Ratio | Max Speed (km/h) |
|------|-------|----------------|
| 1    | 3.833 | 16             |
| 2    | 2.105 | 29             |
| 3    | 1.310 | 47             |
| 4    | 0.919 | 67             |
| 5    | 0.784 | 79             |
| R    | 3.583 | -              |
- Final Drive Ratio: 4.222

## Calculations

### 1. Torque on Wheels (approx)
- Torque in 1st Gear: 3.833 x 4.222 x 69Nm ≈ 1116 Nm
- Torque on wheels: 1116 x 0.1651 ≈ 184 Nm

### 2. Maximum Speed
- Wheel radius: 0.1651 m  
- Top Gear Ratio: 0.784  
- Final Drive Ratio: 4.222  
- Overall Gear Ratio = 0.784 x 4.222 ≈ 3.31  

Vehicle speed formula:  Vehicle Speed (km/h) = (Motor RPM x Wheel Radius) / (2.65 x Overall Gear Ratio)

- At max RPM: 79 km/h  
- At efficient RPM (3500): 65 km/h  
- At low RPM (3000): 56 km/h  
- Accounting for transmission loss → ~75 km/h

### 3. Battery Capacity
- Power required at top speed: 5000 W (approx)  
- Efficiency: 5000 W / 75 km/h ≈ 66.6 Wh/km  
- Range requirement: 150 km  
- Required battery capacity: 66.6 x 150 ≈ 10,000 Wh → 10 kWh  
- Amp-hour rating: 10,000 / 72V ≈ 138 Ah  
- Using 150 Ah for safety and to avoid full discharge

### 4. Packs Available
- NMC: 6.5 kWh  
- LFP: 4.8 kWh  
- LTO: 2 packs, 4.968 kWh
# Motor & Battery Analysis – Santro EV

This Excel file contains detailed motor, gear, and battery calculations for the Santro EV. You can tweak the values such as RPM, gear ratios, wheel size, and battery specifications to see how the torque, top speed, efficiency, and range change.

[Download Excel file](

https://github.com/simardmg/EV-Conversions-and-Projects/raw/0b3b12d9b51a0ec0a6e7a1b146b34c01085e2094/Santro_EV_Motor_Battery_Analysis_Advanced.xlsx)

