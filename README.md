# -Induction-Motor-Characteristics-and-Performance-Analysis-Using-MATLAB
This is my Numerical Technique Laboratory Project . in this project, I developed a MATLAB Designer App application that estimates induction motor’s equivalent-circuit parameters from standard lab tests (DC, no-load, and locked-rotor) or direct inputs, then simulates performance across slip to plot torque–speed, power, loss, and efficiency curves and report starting torque, maximum (pull-out) torque, and maximum slip.
The application supports two methods of motor analysis: 
1. **Standard Laboratory Test Method**
- DC test
- No-load test
- Locked-rotor test
2. **Direct Parameter Input Method**
- Stator resistance and reactance
- Rotor resistance and reactance
- - Core-loss resistance
  - - Magnetizing reactance
    - - Supply voltage
      - - Frequency
        - - Number of poles
          - - Slip
Using the laboratory test data, the application calculates the induction motor equivalent-circuit parameters, including: - Stator resistance, \(R_1\) - Stator leakage reactance, \(X_1\) - Rotor resistance, \(R_2\) - Rotor leakage reactance, \(X_2\) - Core-loss resistance, \(R_c\) - Magnetizing reactance, \(X_m\) - Effective rotor resistance, \(R_2/s\) The calculated values are automatically displayed on the induction motor per-phase equivalent-circuit diagram.
## Main Features
- Interactive MATLAB App Designer graphical user interface
- Parameter estimation from DC, no-load, and locked-rotor tests
- Direct-input option for known motor parameters
- Automatic calculation of synchronous speed
- Slip-based motor performance simulation
- Dynamic display of the equivalent-circuit parameters
- Calculation of starting torque
- Calculation of maximum or pull-out torque
- Calculation of slip at maximum torque
- Performance analysis over the complete motor-speed range
- Separate tabs for viewing different motor characteristics
## Performance Curves
The application calculates and plots the following induction motor characteristics:
- Induced torque versus rotor speed
- Converted mechanical power versus rotor speed
- - Rotor copper loss versus rotor speed
  - - Core loss versus rotor speed
    - - Stator copper loss versus rotor speed
      - - Input power versus rotor speed
        -  - Efficiency versus rotor speed
       The torque-speed curve is used to visualise the starting torque, maximum torque, stable operating region, and the reduction of torque near synchronous speed. ## Numerical Calculations For each selected slip value, the application determines the rotor speed using: \[ N_m = (1-s)N_s \] where: - \(N_m\) is the rotor mechanical speed - \(s\) is the slip - \(N_s\) is the synchronous speed The synchronous speed is calculated from: \[ N_s = \frac{120f}{P} \] where: - \(f\) is the supply frequency - \(P\) is the number of poles The application then uses the induction motor equivalent circuit to calculate stator current, rotor current, air-gap power, converted power, different motor losses, developed torque, input power, and efficiency.

![Screenshot](assets/Screenshot%202026-06-21%20011011.png)





![Screenshot](assets/Screenshot%202026-06-21%20011326.png)

![Screenshot](assets/Screenshot%202026-06-21%20011530.png)



![Screenshot](assets/Screenshot%202026-06-21%20011556.png)


![Screenshot](assets/Screenshot%202026-06-21%20011615.png)

![Screenshot](assets/Screenshot%202026-06-21%20011625.png)

![Screenshot](assets/Screenshot%202026-06-21%20011755.png)

![Screenshot](assets/Screenshot%202026-06-21%20011830.png)

![Screenshot](assets/Screenshot%202026-06-21%20011843.png)

![Screenshot](assets/Screenshot%202026-06-21%20011857.png)

![Screenshot](assets/Screenshot%202026-06-21%20011908.png)



![Screenshot](assets/Screenshot%202026-06-21%20012659.png)

![Screenshot](assets/Screenshot%202026-06-21%20012718.png)

![Screenshot](assets/Screenshot%202026-06-21%20012737.png)

![Screenshot](assets/Screenshot%202026-06-21%20012755.png)

![Screenshot](assets/Screenshot%202026-06-21%20012812.png)

![Screenshot](assets/Screenshot%202026-06-21%20012831.png)

![Screenshot](assets/Screenshot%202026-06-21%20012848.png)

![Screenshot](assets/Screenshot%202026-06-21%20012859.png)

![Screenshot](assets/Screenshot%202026-06-21%20012911.png)

![Screenshot](assets/Screenshot%202026-06-21%20012920.png)

![Screenshot](assets/Screenshot%202026-06-21%20023803.png)








