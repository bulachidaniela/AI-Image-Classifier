
# AI Image Classifier

An interactive web application that uses **Deep Learning** to classify images with **MobileNetV2**. Users can upload images and get real-time predictions of the top 3 object classes.

## Features

- Upload images in JPG or PNG format.
- Predict objects in images using a pre-trained MobileNetV2 model.
- Display top 3 predictions with confidence scores.
- Built with **Streamlit** for an easy-to-use web interface.

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/project3.git
cd project3
````

2. Create a virtual environment and install dependencies:

```bash
python -m venv .venv
source .venv/bin/activate  # On Mac/Linux
.venv\Scripts\activate     # On Windows
pip install -r requirements.txt
```

3. Run the app:

```bash
streamlit run main.py
```

## Technologies Used

* Python 3.11
* TensorFlow (MobileNetV2)
* Streamlit
* OpenCV
* Pillow (Image Processing)
