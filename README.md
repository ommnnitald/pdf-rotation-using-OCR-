# pdf-rotation-using-OCR-
PDF Text Rotation Correction with Tesseract OCR

PDF Text Rotation Correction
Overview

This project is a Python script that leverages the power of Tesseract OCR (Optical Character Recognition) and image processing to correct text orientation in PDF files. Many PDFs may contain text that is rotated at different angles, making it difficult to extract and process the text accurately. This script aims to automatically detect the rotation angle of the text in a PDF, correct it, and save the modified PDF with the rotated text.
Features

    Reads a PDF file and converts each page to an image using pdf2image.
    Applies image processing techniques to extract text from the images using Tesseract OCR with pytesseract.
    Detects and analyzes the orientation of the extracted text to determine the rotation angle.
    Rotates the text to the correct orientation and saves the modified PDF with the corrected text.
    Customizable image processing techniques and text analysis to accommodate different use cases.

Requirements

    Python 3.x
    pytesseract library for text extraction using Tesseract OCR.
    pdf2image library for converting PDF pages to images.
    opencv-python library for image processing.

Usage

    Clone the repository to your local machine.
    Install the required dependencies using pip install pytesseract pdf2image opencv-python.
    Run the pdf_text_rotation_correction.py script with your input PDF file path.
    The script will process the PDF, analyze the text orientation, and generate a corrected output PDF file.

Limitations

    The accuracy of text rotation correction depends on the quality of the PDF and the text extraction from images using Tesseract.
    The script may not work optimally with certain complex PDF layouts or fonts.
    The rotation detection and correction algorithms may need further tuning for specific use cases.

Contribution

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
License

This project is licensed under the MIT License.
Acknowledgments

    The script is inspired by the need to handle PDFs with text rotated at various angles.
    Thanks to the developers of Tesseract OCR, pdf2image, and OpenCV for providing the underlying technologies used in this project.

Contact

If you have any questions or inquiries about the project, you can contact me at your-ommnnitald@gmail.com.
