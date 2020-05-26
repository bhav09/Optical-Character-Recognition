# Optical-Character-Recognition
This Repository is dedicated to OCR , its purpose , installation , how to use, application etc

-->What is OCR, its purpose and its application : https://en.wikipedia.org/wiki/Optical_character_recognition

-->Installation

Dependency :
PILLOW : pip install pillow

pytesseract : pip install pytesseract

tesseract-ocr : pip install tesseract-ocr

For Windows users:

1.Install tesseract using windows installer available at: https://github.com/UB-Mannheim/tesseract/wiki

2.See where tesseract is being installed. For eg if the path is :C:\Users\USER\AppData\Local\Tesseract-OCR 

3.Set the tesseract path in the script before calling image_to_string:
    
    pytesseract.pytesseract.tesseract_cmd = r'C:\Users\USER\AppData\Local\Tesseract-OCR\tesseract.exe'
    
4. Refer the code for better understanding

