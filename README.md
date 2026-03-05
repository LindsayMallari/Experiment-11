# Experiment 11: Sampling and Reconstruction

## Objectives
- Observe sampling using **Natural Sampling** and **Sample-and-Hold**.
- Reconstruct a sampled signal using a **tuneable low-pass filter**.
- Demonstrate **aliasing** and verify the **Nyquist-Shannon Sampling Theorem**.

## Materials
- Emona Telecomms-Trainer 101 (power pack)
- Dual-channel 20 MHz oscilloscope
- Modules: Master Signals, Dual Analog Switch, Speech, Tuneable LPF, VCO
- BNC-to-banana and patch leads

## Procedure

### Part A: Sampling a Simple Signal
1. Connect **2 kHz sine output** to the **Dual Analog Switch input**.
2. Connect **8 kHz digital output** to the **control input**.
3. Display the sine wave on **CH1** and connect the switch output to **CH2**.
4. Observe **Natural Sampling**.
5. Modify the setup to use **Sample-and-Hold** and observe the waveform.

### Part B: Sampling Speech
1. Replace the sine input with the **Speech module output**.
2. Set the oscilloscope to **2 ms/div**.
3. Speak or sing and observe the sampled speech signal.

### Part C: Signal Reconstruction
1. Reconnect the **2 kHz sine signal**.
2. Connect **Sample-and-Hold output** to the **Tuneable LPF input**.
3. Slowly increase the **cut-off frequency** until the **2 kHz sine wave is reconstructed**.

### Part D: Aliasing
1. Replace the **8 kHz control signal** with the **VCO output**.
2. Decrease the sampling frequency gradually.
3. Observe distortion when the sampling rate falls **below the Nyquist rate**.

## Key Concept
Nyquist Theorem:  
\[
f_s \ge 2f_{max}
\]

If the sampling frequency is lower than this, **aliasing occurs**.
