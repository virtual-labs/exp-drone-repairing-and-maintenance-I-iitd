### Definition of Drone (Quadcopter)

A quadcopter is an unmanned aerial vehicle (UAV) with four rotors, each powered by a motor and propeller. It can be manually controlled or programmed to operate autonomously. Quadcopters are widely used in aerial photography, surveillance, agriculture, and research due to their stable flight performance and precise maneuverability.

### Principle of Drone

Quadcopters rely on two rotors rotating clockwise (CW) and two counter-clockwise (CCW) to balance torque and provide lift.

- *Pitch/Roll:* Controlled by varying the thrust of opposite rotors.  
- *Yaw:* Controlled by adjusting the net torque difference between CW and CCW rotors.  

Unlike helicopters, quadcopters do not use cyclic pitch control; instead, they rely on rotor speed variations for maneuvering.

---

### Components Involved in Battery and PMU Issues

### 1. Drone Battery
The battery is the primary power source of the drone, usually a Lithium Polymer (Li-Po) battery, chosen for high energy density and lightweight.

*Functions:*
- Supplies power to all components (motors, ESCs, FC, PMU, sensors, and payload).
- Provides stable voltage and current for flight.

*Common Issues:*
- Overcharging/Over-discharging → reduces battery lifespan.
- Swelling or puffing → caused by overheating or misuse.
- Loose terminals/wiring → leads to intermittent power supply.
- Reduced capacity → drone may not fly for expected duration.

*User Checks:*
- Inspect battery casing for swelling or leaks.
- Use a battery tester/multimeter to measure voltage.
- Ensure proper soldering of connectors.

---

### 2. Power Management Unit (PMU)
The PMU is responsible for distributing power from the main battery to all drone components. It also regulates voltage and protects against power surges.

*Functions:*
- Distributes correct voltage to flight controller, ESCs, receiver, and sensors.
- Protects electronics from sudden current spikes.
- Provides stable operation by regulating inconsistent battery output.

*Common Issues:*
- Loose or burnt connectors.
- Overheating due to excessive current draw.
- Faulty voltage regulation causing random system failures.

*User Checks:*
- Inspect wiring and solder joints for looseness.
- Test output voltage with a multimeter.
- Replace PMU if it shows inconsistent voltage readings.

---

### 3. Soldering and Connections
Weak or broken soldering can lead to power interruptions. If power is not supplied properly, the drone may fail to start or may shut down mid-flight.

*Common Problems:*
- Cold solder joints (dull or cracked).
- Loose wire connections.
- Burnt tracks on PCB due to short circuits.

*Solution:*
- Re-solder loose joints with proper heat and flux.
- Replace burnt wires or connectors.

---

### 4. Physical Damage
Drone crashes may cause cracks in the battery casing or broken wires around the PMU. Regular inspections prevent further damage.

---

### Troubleshooting Approach
1. *Visual Inspection* – Check battery casing, PMU board, and solder joints.  
2. *Voltage Testing* – Use a multimeter to measure battery voltage and PMU outputs.  
3. *Re-soldering* – Repair loose connections.  
4. *Component Replacement* – Replace damaged battery or faulty PMU.  

---

By maintaining healthy batteries and a properly functioning PMU, the overall safety and efficiency of the drone can be ensured.