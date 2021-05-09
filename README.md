# News-extraction-using-various-py-libs
Mainly using python libraries: PIL, pytesseract, opencv.

**About**
Extract images from the respective newspapers using face detection based on key word search 
after applying OCR on the newspaper images. Display these images as a contact sheet (A collage of images, in a uniform format)

**Process**
1) We have newspaers in .png format inside a zip file
2) We perform OCR of all the newspapers
3) We train our model on detecting human faces (Done very briefly using face detection classifier)
4) We build a function that takes in a keyword (for search). This function can access the OCR text as well as faces.
5) On running, the function performs search and outputs all the related images from the newspapers as a contact sheet
