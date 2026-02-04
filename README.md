# AI Audio-to-MIDI Transcriber 🎹

### Project Goal
Building a modern Automatic Music Transcription (AMT) application. The system aims to isolate instrument tracks from audio files and generate precise MIDI files to be used as interactive learning materials.

---

## 🚀 Development Roadmap
1. **Base Model:** Training a neural network on the **MAESTRO v3** dataset (solo piano).
2. **Preprocessing:** Converting raw audio into CQT (Constant-Q Transform) spectrograms.
3. **AI Architecture:** Implementing a hybrid CRNN (CNN + LSTM) model with an Attention mechanism.
4. **Instrument Isolation:** Integrating source separation models (e.g., Demucs) for multi-instrument support.
5. **Application:** A user interface for seamless learning based on the generated MIDI files.

## 🛠 Tech Stack
- **Language:** Python 3.x
- **Environment:** Google Colab / GPU
- **Libraries:** TensorFlow/PyTorch, Librosa, PrettyMIDI, Mido
- **Dataset:** [MAESTRO Dataset](https://magenta.tensorflow.org/datasets/maestro)

## 📁 Project Structure
- `/data` - Scripts for downloading and preprocessing the MAESTRO dataset.
- `/models` - Neural network architecture definitions and trained weights.
- `/notebooks` - Colab notebooks containing experiments and research.
- `/utils` - Helper scripts for audio/MIDI conversions and signal processing.

## ⚖️ License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.
