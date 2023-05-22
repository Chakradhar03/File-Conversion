# File-Conversion

# Project Name: 8-bit Grayscale to 24-bit Grayscale BMP Image Converter

## Description:
This project focuses on converting an 8-bit grayscale image to a 24-bit grayscale BMP image format. The BMP (Bitmap) format, developed by Microsoft, is widely used for storing images. The program takes an uncompressed 8-bit BMP image that stores pixel data in grayscale values and converts it to a 24-bit BMP image, where pixel data is represented in RGB values.

## Instructions:
To run the code, follow these steps:

1. Unzip the project folder.
2. Open the command prompt or terminal.
3. Navigate to the project directory.
4. Run the command `make` to compile the code.
5. Run the command `./output` to execute the program.
6. Place the source image file in the same directory as the code.
7. When prompted, enter the name of the source image file and press Enter. Alternatively, you can enter the path of the source image file.
8. After the conversion process, a file named "output.bmp" will be generated in the project directory.
9. Open "output.bmp" using an image viewer or editor to visualize the converted image.
10. Additionally, the terminal will display the header data of both the sample and target images, providing a verification of the successful conversion.

Note: Make sure the source image is in the BMP format and stored as an 8-bit grayscale image.

Feel free to explore and experiment with different images to observe the conversion results.

## Requirements:
- C compiler (GCC or compatible)
- Standard C libraries

## Limitations:
- The code supports the conversion of uncompressed 8-bit grayscale BMP images only.
- It does not handle compressed or other image formats.
- Ensure that the source image is in the BMP format and stored as an 8-bit grayscale image.

Please refer to the project documentation for more details and examples.
