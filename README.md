# Entity-Extraction
This is collection of notebooks to implement Entity Extraction on semi-structured data.
The scanned receipts data is provided at https://rrc.cvc.uab.es/?ch=13&com=downloads. 

To Generate OCR part:
* Install tesseract: https://github.com/tesseract-ocr/tesseract
* LSTM models: https://github.com/tesseract-ocr/tessdata
* Use generate_tesseract_results.py : https://github.com/Praneet9/Representation-Learning-for-Information-Extraction


Main Notebooks:
1. token_Conv2D: Used the token features to make the prediction if the token is part of entity.
2. Coordinates: Used the coordinates only information to make prediction if the token is part of entity.
3. Attention model: Implements the Attention model and uses coordiantes information fo Entity extraction.
4. Spacy_NER: Employs the Spacy Entity Extraction
