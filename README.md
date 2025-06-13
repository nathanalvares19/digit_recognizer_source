# 🧠 Handwritten Digit Recognizer

This project is a simple AI model that recognizes handwritten digits (0–9) from images using a neural network. Built using Python and trained on the MNIST dataset.

---

## ✨ Features

- Classifies digits from 0 to 9
- Trained on the MNIST dataset
- Web interface (coming soon)
- Lightweight and beginner-friendly

---

## 💾 How to Use Locally

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/handwritten-digit-recognizer.git
cd handwritten-digit-recognizer
```

### 2. Install dependencies
Make sure you have Python 3.7+ installed. Then install required packages:
```bash 
pip install -r requirements.txt
```

### 3. Using the model 
## Initial Setup
1. Open the Jupyter notebook (`.ipynb` file) in your preferred environment
2. Run all cells, before the PREDICT INPUT label, in the notebook sequentially to train/load the model

## Making Predictions

### Step 1: Prepare Your Input Image
1. Locate the `digit.png` file in the repository
2. Open `digit.png` in any image editing software (Paint, GIMP, Photoshop, etc.)
3. Draw your digit on the image following these guidelines:
   - Use a **white background**
   - Draw the digit in **black**
   - Make sure the digit is clearly visible and well-formed

### Step 2: Save and Predict
1. Save the modified `digit.png` file
2. In the Jupyter notebook, find the cell labeled **"Predict"**
3. Run the "Predict" cell to get the model's prediction for your drawn digit

## Tips for Best Results
- Draw digits clearly and avoid overlapping strokes
- Keep the digit centered in the image
- Use consistent black color for drawing
- Ensure good contrast between the digit and white background

## Troubleshooting
- If predictions are inaccurate, try redrawing the digit more clearly
- Make sure the `digit.png` file is saved in the correct location
- Verify that all notebook cells have been executed before running predictions


## ⚠️ Disclaimer
This digit recognition model is for educational and demonstration purposes. **The model is not 100% accurate** and may produce incorrect predictions, especially for:
- Poorly drawn or unclear digits
- Unusual handwriting styles
- Digits that are rotated, skewed, or off-center
- Images with poor contrast or resolution

Results should be interpreted as approximations and not relied upon for critical applications.
