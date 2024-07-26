## Extract Data from Chart

### Description
This project involves developing a software application that uses image processing methods to extract digital data from charts and graphs in image format. The software leverages various computer vision and image processing techniques to identify and digitize the data points and structures within the charts. This is particularly useful for converting graphical data into numerical formats for further analysis and usage.

### Features
- **Image Preprocessing**: Applies preprocessing techniques to enhance the quality of the input image and improve the accuracy of data extraction.
- **Chart Detection**: Uses edge detection and contour analysis to identify and isolate charts within the image.
- **Data Point Extraction**: Extracts data points from the detected charts using methods like Hough Transform, template matching, and OCR (Optical Character Recognition).
- **Data Conversion**: Converts the extracted graphical data into a digital format such as CSV or JSON for easy manipulation and analysis.
- **Visualization**: Provides visual feedback by overlaying the extracted data points on the original image to verify accuracy.

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/batikandemirci/extract_data_from_chart.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Code Structure
- **Image Preprocessing**: Involves steps like grayscale conversion, thresholding, and noise reduction to prepare the image for data extraction.
- **Chart Detection**: Uses techniques like Canny edge detection and contour finding to locate the chart within the image.
- **Data Extraction**: Identifies and extracts data points using a combination of line detection, shape analysis, and OCR.
- **Data Conversion and Visualization**: Converts the extracted data into a digital format and overlays the data points on the original image for verification.

### Future Work
- Improve the accuracy of data point extraction with more advanced machine learning models.
- Add support for extracting data from more complex chart types.
- Enhance the user interface for easier usage and better user experience.

### Contributions
Feel free to fork the repository and submit pull requests. All contributions are welcome!
