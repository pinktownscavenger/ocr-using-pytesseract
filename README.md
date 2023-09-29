# ocr-using-pytesseract
Transalate text extracted from images using Pytesseract and Transalator.

### Installation
1. Clone the repository:
    '''bash
    git clone https://github.com/pinktownscavenger/ocr-with-transalation.git

2. pip install -r requirements.txt

### Usage
To perform OCR and transalation on an image, you can use the following code:

    Replace 'test.png' with file location of image you want to perform OCR on.
        image = cv2.imread('test.png', 0)
    
    Being transalated from 'English' to 'French', change accordingly.
        result = translator.translate(text, 'French', 'English')