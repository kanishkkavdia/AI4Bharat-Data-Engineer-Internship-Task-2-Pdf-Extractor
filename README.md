# AI4Bharat-Data-Engineer-Internship-Task-2-Pdf-Extractor
Extract pdf content from all the url’s present in the google sheet


Libraries required : pandas, pytesseract (also download tesseract ocr and specify it's path Pdf2processor class in pdf2processor.py), pdf2image(also download poppler and specify it's path in the Pdf2processor class in pdf2processor.py), pillow, pathlib

Instructions: To use this assignment--> Run wiki_extractor.py. Enter keyword ,number of urls you want and json filename.

Sample: There is also a demo file made for keyword="History of India" ,no of url =20, filename="out.json". Example of user input is also given in the form of picture.

Code Structure: There are 2 python files:

wiki_api.py: In this python file I have built Wikipedia_info class. It handles user's queries made through wiki_extractor.py and uses these to fetch data through python wikipedia api. The data is further processed and converted to suitable json file.

wiki_extractor.py: This file contains basic command to input user queries and send it to Wikipedia_info class created in wiki_api.py.
