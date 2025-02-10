# Image Captioning Project

This project generates captions for images using a deep learning model trained on an image dataset. The model utilizes a CNN-based feature extractor and an LSTM-based caption generator.

## Features
- Extracts features from images using a CNN-based feature extractor.
- Generates captions using an LSTM-based sequence model.
- Uses a tokenizer for text processing and vocabulary management.

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install tensorflow numpy pandas matplotlib pillow
```

## Setup
### 1. Run the Jupyter Notebook
Before running the main application, you must first run the Jupyter Notebook (`.ipynb` file) to train the model and generate the required files. This step will produce the following files:
- `tokenizer.pkl`
- `model.keras`
- `feature_extractor.keras`

### 2. Move Generated Files
After generating the files, move them to the same directory as `main.py`.

### 3. Run the Application
Once the required files are in place, you can run the main application using:

```bash
python main.py
```

## Usage
- The application takes an image as input and generates a caption based on the trained model.
- Ensure all required dependencies and files are properly set up before running the script.

## Notes
- The model is trained on a specific dataset, and performance may vary based on the dataset quality.
- Further fine-tuning and dataset modifications can improve results.

## License
This project is open-source and available for modification and distribution.

---


