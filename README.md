# VocalEmotion_conv 🎭🔁🔊

A deep learning-based project for emotional voice conversion using the CREMA-D dataset. This project transforms speech from one emotional state (e.g., sad) into another (e.g., angry, happy, fearful, etc.), enabling emotion-based speech synthesis and affective computing applications.

## 🚀 Features

- Emotion conversion from source (e.g., sad) to target (e.g., angry)
- Preprocessing using the CREMA-D dataset
- Spectrogram extraction & manipulation
- MelGAN / AutoVC (or other vocoders/models as used)
- PyTorch/TensorFlow-based modeling
- Evaluation via waveform listening & spectrogram comparison

## 📂 Dataset

This project uses the [CREMA-D Dataset](https://zenodo.org/record/3666821), which contains 7442 clips from 91 actors across 6 emotions:  
**Anger, Disgust, Fear, Happy, Neutral, and Sad**.

## 🛠️ Requirements

- Python 3.8+
- NumPy, Librosa, Matplotlib
- PyTorch / TensorFlow
- Jupyter Notebook
- (Optional) Gradio / Streamlit for demo UI

```bash
pip install -r requirements.txt
Sure! Here's the section you provided formatted correctly in **Markdown** for your GitHub `README.md`:

````markdown
## 📈 Training & Inference

### 1. Preprocessing
```python
# Load audio, extract features (Mel spectrograms)
````

### 2. Training

```python
# Train your model (e.g., encoder-decoder, AutoVC, CycleGAN, etc.)
```

### 3. Emotion Conversion

```python
# Convert input emotion (e.g., SAD) to target (e.g., ANGRY)
```

### 4. Output

```python
# Synthesize waveform using vocoder and save output
```


## 🧠 Future Work

* Real-time conversion
* Integration with chatbots or avatars
* Multi-lingual emotion conversion

