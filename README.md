# 🧠 Deepfake Detection System 🔍  
A cutting-edge deepfake detection app built with passion by [ChampGok](https://github.com/rajagokulakrishnan676).  
This tool analyzes images, videos, and audio files to determine whether content has been manipulated using AI — a key defense in today’s digital age.

---

## 🚀 Features

- 🎞️ **Video Detection** – Detect deepfake elements frame-by-frame using PyTorch & OpenCV.
- 🎙️ **Audio Detection** – Analyze speech patterns to identify voice synthesis or AI-generated audio.
- 🖼️ **Image Forensics** – Inspect facial inconsistencies, lighting, and blending using CNN-based classifiers.
- 📊 **Real-Time Output** – Instant detection results in an intuitive interface.
- 🧠 **Grad-CAM Visualization** – See what parts of the face the model focuses on.
- ⚙️ **Modular Processor Scripts** – Clean, separate processing for image, video, and audio inputs.
- 🎯 **High Accuracy** – Trained with diverse deepfake datasets and real-world samples.

---

## 🛠️ Tech Stack

| Technology      | Role                       |
|----------------|----------------------------|
| `Python`        | Core programming language  |
| `PyTorch`       | Deep learning framework    |
| `OpenCV`        | Video & image processing   |
| `NumPy / Librosa` | Audio signal processing |
| `Streamlit`     | UI for interaction         |
| `Grad-CAM`      | Visual model interpretation|

---

## 🗂️ Project Structure


---

## 📦 Installation

> ⚠️ Python 3.8+ recommended

```bash
# Clone the repository
git clone https://github.com/rajagokulakrishnan676/maya360.git
cd maya360/datathon

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run home.py
