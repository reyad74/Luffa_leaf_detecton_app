# Luffa Leaf Disease Detection App

A Flask-based web application for detecting luffa leaf diseases using a trained TensorFlow deep learning model.

### Home Page
![Home Page](E:\Luffa_leaf_detecton_app\Luffa_leaf_detecton_app\home.png)

### Disease Detection Result
![Result Page](E:\Luffa_leaf_detecton_app\Luffa_leaf_detecton_app\Result.png)

## Features
- Upload leaf images (PNG, JPG, JPEG)
- Predict 6 leaf disease classes
- Display detected disease and suggested medicine
- User-friendly web interface

## Disease Classes
1. Alternaria Leaf Spot
2. Angular Leaf Spot
3. Downy Mildew
4. Holed
5. Mosaic Virus
6. Fresh (Healthy)

## Installation

### Prerequisites
- Python 3.7+
- pip

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Luffa-Leaf-Detection-App.git
   cd Luffa-Leaf-Detection-App
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   .\venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download the trained model `best_model.h5` and place it in the project directory.

5. Run the Flask app:
   ```bash
   python app.py
   ```

6. Open your browser and navigate to:
   ```
   http://127.0.0.1:5000/
   ```

## Usage
1. Upload a leaf image
2. The app will predict the disease
3. View the suggested medicine/treatment

## Project Structure
```
Luffa-Leaf-Detection-App/
├── app.py
├── requirements.txt
├── README.md
├── static/
│   ├── css/
│   │   └── style.css
│   └── uploads/
├── templates/
│   ├── index.html
│   └── result.html
└── best_model.h5
```

## Technologies Used
- Flask (Web Framework)
- TensorFlow/Keras (Deep Learning)
- NumPy (Data Processing)
- scikit-image (Image Processing)

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Md. Reyadul Islam Reyad

## Acknowledgments
- TensorFlow/Keras documentation
- Flask documentation