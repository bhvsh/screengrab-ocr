# Python-ScreenGrabber

A simple Python application that captures screenshots and performs optical character recognition (OCR) on the text within the image. The OCR result is then printed out for easy access to the text contained within the screenshot. The user can use this tool to quickly and easily extract text from screenshots without the need for manual typing.

Requires installation of Tesseract Open Source OCR Engine.<br>
Link: https://tesseract-ocr.github.io/tessdoc/Installation.html

![Screenshot of the ScreenGrabber application in use - Windows](https://i.imgur.com/Pp5SEDN.png)

## Limitations

Please note that while this application uses Tesseract for OCR, it may not provide accurate results on images with a DPI lower than 300. For best results, it's recommended to use screenshots with a DPI of at least 300.

For more information, please see the following link:<br>
https://tesseract-ocr.github.io/tessdoc/ImproveQuality.html#rescaling