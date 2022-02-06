# AI4Bharat-Data-Engineer-Internship-Task-2-Pdf-Extractor
Extract pdf content from all the url’s present in the google sheet


Libraries required : pandas, pytesseract (also download tesseract ocr and specify it's path in the Pdf2processor class in pdf2processor.py), pdf2image(also download poppler and specify it's path in the Pdf2processor class in pdf2processor.py), pillow, pathlib

Instructions: 

*Tl;dr---> Run pdf_extractor.py, if you have downloaded the csv file.

*Download google sheet and save it in the project folder as "data_pdf.csv".

*Create url column for storing urls. The file can be accessed with pandas.

*These 2 steps can be skipped as I have included the csv file in this project and you can download it directly.
          


Sample: A ScreenShot of Json file is given.

Code Structure: There are 3 python files:

* link

wiki_extractor.py: This file contains basic command to input user queries and send it to Wikipedia_info class created in wiki_api.py.
