
## Exp 6 Simulation of Optical Communication System

## Aim

To simulate an optical communication system using OptiPerformer, observe the effect of fiber length on received power, Q-factor, BER, and eye diagram, and analyze system performance across increasing transmission distances.

---

## **Tools Required**

1. **Computer/Laptop**
   – Windows OS (OptiPerformer supported versions)

2. **OptiPerformer Software**
   – Installed from Optiwave (free)

3. **Simulation File**
   – `Introduction_OptiPerformer.osp`

4. **Internet Connection**
   – For downloading the software (not required after installation)

5. **Basic Optical System Components (within the software):**

   * PRBS/Binary Source
   * Electrical Pulse Generator
   * Laser Diode
   * External Modulator
   * Optical Fiber
   * Optical Power Meter
   * Photodiode
   * Low-Pass Filter
   * Decision Circuit
   * BER Analyzer

---

## Procedure

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**
![WhatsApp Image 2025-11-17 at 11 07 46_8e98399b](https://github.com/user-attachments/assets/0d2a64d7-2754-4ef3-a1f0-690bfdf34516)

---

## Graphs

<img width="912" height="975" alt="Screenshot 2025-11-12 072050" src="https://github.com/user-attachments/assets/566a99a6-5102-48bc-9e9a-da70cd664c39" />

---
---

<img width="912" height="975" alt="Screenshot 2025-11-12 072143" src="https://github.com/user-attachments/assets/c07e2dac-efe7-420a-9ce3-c07f8af41f87" />

---
---

<img width="912" height="975" alt="Screenshot 2025-11-12 072251" src="https://github.com/user-attachments/assets/e25a0844-1a26-4026-aad6-9584f15d2a96" />

---
---

## RESULT

**Result:**
The optical communication system was successfully simulated using **OptiPerformer**.
As the **fiber length increased** from **50 km to 150 km**, the following trends were observed:

* **Received optical power** decreased due to fiber attenuation.
* **Q-factor** gradually decreased, indicating signal quality degradation.
* **Bit Error Rate (BER)** increased with distance, showing higher error probability.
* The **eye diagram** became more closed at longer fiber lengths, confirming dispersion and noise effects.

Hence, the simulation verified that **optical signal performance deteriorates with increasing fiber length** due to attenuation and dispersion losses.
