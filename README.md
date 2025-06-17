# Dog Breed Prediction Streamlit App

This project is a Streamlit web application for predicting dog breeds from images using a pre-trained deep learning model.

## Project Structure

- `main_app.py` - Main Streamlit application file.
- `dog_breed.h5` - Pre-trained Keras model for dog breed classification.
- `requirements` - List of required Python packages.

## Setup

1. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

2. **Run the app:**
   ```
   streamlit run main_app.py
   ```

3. **Usage:**
   - Upload a dog image in the app.
   - The app will predict the breed using the model in `dog_breed.h5`.

## Requirements

- Python 3.7+
- Streamlit
- TensorFlow / Keras
- Pillow
- (See `requirements.txt` for full list)

## Notes

- Make sure `dog_breed.h5` is in the same directory as `main_app.py`.
- The app uses a deep learning model trained to classify dog breeds from images.

---