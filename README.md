# Python3-Remove-Watermark
First, the program use python3. 
A simple program to remove the watermark from a PDF file. 
Original code from [here](https://github.com/LJSthu/Python-Remove-Watermark)

### how?

1. convert the PDF file into images using `pdf2image`
2. convert the images to numpy array
3. find the specific pixel by watermarks' rgb values and change them into (255,255,255)
4. save the modified images


### environment
`pdf2image`: pip3 install pdf2image
`scikit-image`: pip3 install scikit-image
`pathlib`: pip3 install pathlib

### usage
Change pdf path in watermark.py for your owm pdf file locations. Then `python3 watermark.py`
Output will be in the same dir.

### todo
1. It is plan to use opencv to drop watermark.
2. Support image file directlly.