# Quantum Emoji Encoder

The **Quantum Emoji Encoder** is a playful yet rigorous model that represents human emotions as *quantum superpositions*.  
It mathematically maps emotional valence, tone (sarcasm phase), and expressive uncertainty to a qubit state on the Bloch sphere.

## 🧠 Concept Overview

- Each emotion is modeled as a **basis state** |eₖ⟩.
- Internal affective states exist as **superpositions** of these basis states.
- Emoji selection represents a **quantum measurement collapse**.
- Emotional ambiguity is quantified by **Shannon entropy**.

## 📘 Mathematical Framework

|ψ⟩ = α|sad⟩ + β|happy⟩, with |α|² + |β|² = 1

- θ : valence angle (negative to positive mood)
- φ : sarcasm phase (tone modulation)
- Entropy:  
  H = −[p log₂(p) + (1−p) log₂(1−p)]

The system evolves on the Bloch sphere, where
valence and tone define the state vector orientation.

## 📊 Figures

1. emotional_qbit.png — Bloch-sphere representation of emotional qubit  
2. entropy_emotion.png — Entropy vs. emotional valence  
3. quantum_phase_heatmap.png — Tone-phase interference map  
4. multi_emoji_superposition.png — Multi-emoji superposition probabilities  
5. wave_func_collaps.png — Temporal collapse visualization  

## ⚙️ How to Reproduce

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/quantum-emoji-encoder.git
   cd quantum-emoji-encoder
   ```

2. Run the simulation in Python:
   ```bash
   python quantum_emoji_encoder.py
   ```

3. Compile the LaTeX paper:
   ```bash
   pdflatex emoji.tex
   ```

## 🧩 Dependencies

- Python ≥ 3.9  
- NumPy, Matplotlib  
- LaTeX (pdfLaTeX compiler)

## 📄 Citation

If you use this work, please cite:
> Nilanjan Panda, *Quantum Emoji Encoder: A Qubit-Based Model of Emotional Expression*, 2025.

---
Inspired by quantum cognition, affective computing, and information theory.
