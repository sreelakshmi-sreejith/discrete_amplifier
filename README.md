# 🔊 Discrete Audio Amplifier (Class AB)

## 📌 Overview
This project presents the design and implementation of a discrete audio amplifier using Bipolar Junction Transistors (BJTs) to drive an 8Ω speaker with approximately 10W RMS output power.

The amplifier is designed for high fidelity, low distortion, and efficient operation using a Class AB configuration.

## 🎯 Objectives
- Design a BJT-based audio amplifier  
- Achieve ~10W output power  
- Minimize distortion using proper biasing  
- Ensure thermal stability and efficiency  


## ⚙️ Circuit Description

The amplifier consists of multiple stages:

### 🔹 Pre-amplifier
- Uses transistor (2N3904)  
- Conditions input signal  

### 🔹 Voltage Amplifier
- Provides signal gain  

### 🔹 Power Amplifier
- Uses TIP31 (NPN) and TIP32 (PNP)  
- Drives 8Ω speaker
- 
## 🛠️ Components Used

| Component | Value |
|----------|------|
| Supply Voltage | 12V |
| Speaker Load | 8Ω |
| Transistors | TIP31, TIP32, 2N3904 |
| Diodes | 1N4148 |
| Capacitors | 1µF, 1000µF |
| Resistors | 390Ω, 1.8kΩ, 330Ω, 33Ω |



👉 These values confirm near 10W performance :contentReference[oaicite:0]{index=0}  

---

## ⚙️ Working Principle

- Input signal passes through coupling capacitor  
- Transistor amplifies signal  
- Output stage drives speaker  
- Feedback reduces distortion  


## 🔌 Circuit Diagram

![Circuit](images/circuit.png)

👉 The circuit (page 9) shows:
- Push-pull output stage (TIP31 & TIP32)
- Biasing network
- Coupling capacitors :contentReference[oaicite:1]{index=1}  


## 📊 Results
- Output Power ≈ 8.4W – 10W  
- Efficient Class AB operation  
- Low distortion audio output  
- Stable thermal performance  


## ▶️ How to Use
1. Build circuit on PCB/breadboard  
2. Provide 12V DC supply  
3. Connect audio input  
4. Attach 8Ω speaker  
5. Observe amplified output  

## 🔧 Applications
- Audio amplification systems  
- Speaker drivers  
- Home audio electronics  
- Embedded sound systems  

## 🚀 Future Scope
- PCB design optimization  
- Heat sink improvements  
- Higher power output  
- Integration with digital audio systems  


## 👩‍💻 Author
**Sreelakshmi S S**  
ECE | Embedded Systems | VLSI  

## 📌 Conclusion
The Class AB amplifier successfully delivers high-quality audio output with good efficiency and minimal distortion, demonstrating practical analog circuit design principles.

