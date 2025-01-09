# Realtime Malicious E-Commerce Website Detector

## Overview

The **Realtime Malicious E-Commerce Website Detector** is a browser extension designed to help users detect deceptive or malicious shopping websites. This extension utilizes machine learning (ML), Optical Character Recognition (OCR), and Natural Language Processing (NLP) techniques to analyze and evaluate the trustworthiness of online stores in real-time. By scanning both textual and image-based content, the extension provides instant feedback and highlights potentially misleading elements to ensure safer online shopping experiences.

### Key Features
- **Browser Extension**: Seamless integration with popular browsers (e.g., Chrome, Firefox) to analyze websites in real-time.
- **Machine Learning**: Classifies websites as "safe" or "malicious" based on textual content using a trained Random Forest classifier.
- **Optical Character Recognition (OCR)**: Extracts text from images (e.g., banners, ads) using OpenCV and Tesseract to detect hidden deceptive content.
- **Natural Language Processing (NLP)**: Analyzes textual content (reviews, product descriptions) to identify patterns of misleading language or fraud.
- **Real-time Alerts**: Highlights suspicious elements on the website with a visual cue (e.g., red borders, yellow backgrounds).
- **User-friendly Interface**: Provides easy-to-understand alerts and highlighted suspicious elements on e-commerce websites.

## Tools & Technologies

- **Programming Language**: Python (for backend machine learning and OCR processing)
- **Libraries**:  
  - **Scikit-learn**: For building and training the machine learning model.
  - **NLTK**: For natural language processing and text analysis.
  - **OpenCV**: For image processing and optical character recognition (OCR).
  - **Flask**: For creating the backend server that handles real-time predictions.
- **Frontend**: Browser Extension (JavaScript, HTML, CSS)
- **OCR**: Tesseract (via OpenCV and pytesseract)
- **Deployment**: Flask server (can be deployed on cloud platforms like Heroku, AWS, or run locally)

## Installation & Setup

### Prerequisites
1. **Python 3.x** installed on your machine.
2. A browser that supports extensions (e.g., Chrome, Firefox).
3. **Tesseract-OCR** installed on your system for OCR functionality (available [here](https://github.com/tesseract-ocr/tesseract)).

### Step 1: Install Backend Dependencies
Clone the repository and install the necessary Python dependencies:

```bash
git clone https://github.com/your-username/malicious-website-detector.git
cd malicious-website-detector
pip install -r requirements.txt
