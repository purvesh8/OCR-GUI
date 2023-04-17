# OCR Tool

OCR Tool is a Python application for Optical Character Recognition (OCR) on images. It allows users to open an image file, select areas of interest, and process the selected areas to extract text information from the image.

## Features

- Open and display images in common formats such as JPG, JPEG, PNG, BMP, and GIF.
- Select areas of interest on the image using a graphical user interface.
- Process the selected areas to perform OCR and extract text information from the image.
- Display the original image, thresholded image, and processed image for visual analysis.
- Supports global thresholding and Otsu's thresholding for image binarization.
- Applies morphological operations like erosion and dilation for image preprocessing.

## Prerequisites

- Python 3.x installed on your system
- Required Python libraries: cv2, matplotlib, tkinter, pandas, PIL (pillow), pytesseract

## Installation

1. Clone the repository to your local machine using `git clone` command.
2. Install the required Python libraries using `pip install` command:
3. Run the `ocr_tool.py` script to start the application:


[{"metadata":{"trusted":true},"cell_type":"code","source":"","execution_count":null,"outputs":[]}]

## Usage

1. Click on the "Open Image" button to open an image file.
2. Use the mouse to select areas of interest on the image.
3. Click on the "Process Image" button to perform OCR on the selected areas.
4. The extracted text information will be displayed in a popup message box.
5. Optionally, you can analyze the original image, thresholded image, and processed image for visual inspection.



## Acknowledgements

- This project utilizes the Tesseract OCR engine developed by Google.
- Image processing operations are performed using OpenCV library.
- GUI is implemented using tkinter library.
- Image display and manipulation are done using PIL (pillow) library.
- Data analysis and manipulation are done using pandas library.
- Visualization is done using matplotlib library.

