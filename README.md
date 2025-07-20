# Facial Aging Using SAM

This project implements a facial aging pipeline using *Segment Anything Model (SAM)* along with deep learning techniques to simulate the visual effects of aging on human faces. It segments the facial regions, applies aging transformations, and visualizes results.

## 🧠 Features

- Uses Meta’s Segment Anything Model (SAM) for face segmentation.
- Applies aging effects based on facial regions (wrinkles, tone, shape).
- Generates side-by-side comparisons of original and aged faces.
- Contains visual analysis like pixel intensity, facial region changes, and similarity graphs.

## 🗂 Project Structure

Facial_Aging_Using_SAM/ ├── notebooks/             # Jupyter notebooks for experimentation ├── results/               # Output images and graphs ├── models/                # SAM and styleGAN model logic ├── run_aging.py           # Main aging pipeline ├── requirements.txt       # Python dependencies

## 🛠 Requirements

- Python 3.8+
- PyTorch
- OpenCV
- Matplotlib
- SAM (Segment Anything)
- NumPy

Install with:

```bash
pip install -r requirements.txt


🤖 Future Work

Add face rejuvenation

Deploy as a web app

Use real-time webcam input


📬 Contact

If you found this project useful or have suggestions, feel free to reach out or create an issue.
