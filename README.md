# AC to DC Mobile Charger using 7805 Voltage Regulator

This project demonstrates the design and working of a simple mobile charger circuit that converts **230V AC mains supply into regulated 5V DC output** suitable for charging electronic devices.

The circuit follows the basic stages of a linear power supply including voltage step-down, rectification, filtering, and voltage regulation.

---


## Circuit Diagram

![Circuit Diagram](circuit.op)

---

## LM7805
![LM7805](78xx Series.zip)


## Components Used

- Step-down transformer (230V AC → 12V AC)
- Bridge rectifier (4 × 1N4007 diodes)
- Filter capacitor (1000 µF)
- Voltage regulator IC (LM7805)
- Output capacitor (10 µF)
- Load resistor (5.5 Ω)
- AC source (230V, 50Hz)

---

## Working Principle

### 1. Step-down Transformer
The transformer reduces the high AC mains voltage (230V AC) to a lower AC voltage (around 12V AC) and provides electrical isolation.

### 2. Bridge Rectifier
Four 1N4007 diodes form a full-wave bridge rectifier that converts AC voltage into pulsating DC.

### 3. Filter Capacitor
A large capacitor smooths the pulsating DC and reduces ripple voltage.

### 4. Voltage Regulator (LM7805)
The LM7805 linear voltage regulator produces a stable **5V DC output**, ensuring safe charging for electronic devices.

### 5. Output Capacitor
The output capacitor stabilizes the voltage and prevents oscillations.

---

## Output Characteristics

The circuit produces a regulated **5V DC output** suitable for powering low-voltage electronic devices.

The project also analyzes:
- Transformer output waveform
- Rectifier output waveform
- Regulated DC output

---

## Applications

- Mobile phone chargers
- DC power supply units
- Embedded systems power supply
- USB powered devices

---

## Key Concepts Demonstrated

- AC to DC conversion
- Bridge rectifier operation
- Voltage filtering using capacitors
- Linear voltage regulation
- Power supply design

---

## Tools Used

- LTspice simulation
- Oscilloscope measurement
- Analog circuit design

---

## Author

Aryan Kose  
