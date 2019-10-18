# Data_Poltergeist
The following work was created during 36hrs spent at Ingenious Hackathon 2019

PROJECT WORKFLOW :

-> Save the first page of pdf as jpeg/png/jpg format and feed its path to segmentation.ipynb notebook.
-> run the "segmentation.ipynb" notebook to create bounding boxes representing placement of text columns on the page.
-> this creates a set of seperate images of bounding boxes above detected.
-> run ocr.py to extract text-data from those set of images and display it in string format.
-> save the exteracted text in a .json file (underprogress).

 
