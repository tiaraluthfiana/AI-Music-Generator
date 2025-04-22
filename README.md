# 🎵 Simple Music Generator Using LSTM

This project demonstrates how to use **Long Short-Term Memory (LSTM)**, a type of Recurrent Neural Network (RNN), to create a basic generative music model. The model is trained on musical note sequences and generates new music patterns that mimic the learned style.

## 🚀 Features
- Uses LSTM for sequence learning.
- Trains on MIDI-like note sequences.
- Generates new music based on learned patterns.
- Simple and easy-to-understand Python implementation.

## 🧠 How It Works
LSTM networks are designed to handle sequential data and remember long-term relationships, making them perfect for music generation. The model learns the structure of melodies and rhythms and then predicts new sequences to create music.

## 💻 Requirements
- Python 3.x  
- TensorFlow or Keras  
- Numpy  
- Music21 (for MIDI handling)  

Install dependencies with:

```bash
pip install tensorflow numpy music21
```

## 📂 Usage
1. Prepare your MIDI dataset.
2. Train the model using `train.py`.
3. Generate new music using `generate.py`.
4. Export the output to MIDI format.

## 🎧 Output
The model produces sequences of notes that can be converted into MIDI files and played using any standard MIDI player.
