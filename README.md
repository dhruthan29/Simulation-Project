# Folded cascoded operational amplifier

- Druthan M D

  Electronics and Communication Engineering

  NIE Mysore, India

  2024lec_druthanmd_a@nie.ac.in

- Akash H A

  Electronics and Communication Engineering

  NIE Mysore, India
  
  2024lec_akashha_a@nie.ac.in

### Objective:
   A folded cascode operational amplifier is designed to enhance the gain, bandwidth, and output swing while maintaining a relatively low supply voltage. The key objectives of this topology include:

### Design Specifications: 
 - Usually ranges between 1.8V to 5V for modern CMOS designs
 - Proper High gain is achieved using cascodestructures; typically, it can be in the range of 60-90dB.
 - current mirroring ensures stable operation.

### Design Description:

- Converts differential signals into a current that flows into the cascode stage.
- Provide high output resistance and improve gain.
- Ensures stable operation and sets the current levels.
- Drives the load and optimizes voltage swing
- A reference current is mirrored across the circuit so as to bias currents source loads.

### Design Calculations:
- Assumptions and Values used
- M12 and M13 are identical
- M8 and M9 are identical
- M10 and M11 are identical
- M1 and M2 are identical
- M3 and M7 are identical
- Higher current flows in outer circuit to provide high swing, than in the inner circuit
- µpCox = 100 μAV-2 and unCox = 200 μAV-2
- Vthp = 0.3 V and Vthn = 0.3v
- Power 18uW
- Vdd = 1.3V
- Id=8uW/1.3V = 10uA

### Circuit Diagram


### Simulation Output

### Conclusion 
A folded cascode operational amplifier is a powerful design that enhances gain, bandwidth, and output swing while maintaining low voltage operation. By strategically "folding" the cascode transistors, this topology balances efficiency and performance, making it ideal for high-speed and precision applications.Its ability to provide high gain, wide bandwidth, and improved common-mode rejection makes it a key choice in analog signal processing, analog-to-digital converters, and low-noise circuits. Careful transistor sizing and biasing ensure stability, efficiency, and optimal performance.
