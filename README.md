# License-Plate-Recognition  


This project focuses on recognizing license plates from vehicle images using a combination of image processing and data analysis techniques. It includes detecting license plate locations and extracting the recognized text from them.

# Project Overview
The notebook performs the following tasks:

* Loads and merges two datasets: one for license plate detection and one for recognition.

* Visualizes bounding boxes of license plates on vehicle images.

* Crops the license plates from the original images.

* Displays the recognized text (OCR output) for each license plate.

* Saves the cropped license plate images into a folder.

# Dataset Information
The project uses two CSV files:

* Licplatesdetection_train.csv: Contains bounding box coordinates for license plates.

* Licplatesrecognition_train.csv: Contains the corresponding recognized text (OCR output) for each plate.

Both datasets are merged using the img_id key.

# Technologies Used
* Python

* Pandas: Data manipulation

* OpenCV: Image processing (bounding box drawing, cropping)

* Matplotlib: Visualization of results

# Key Functionalities
* Draws bounding boxes on car images to locate license plates.

* Crops license plates from full images using coordinates.

* Displays recognized text for visual validation.

* Saves cropped license plate images in a dedicated folder.

# Output Example
The notebook will display:

* Original image with license plate bounding boxes.

* Cropped license plate images.

* OCR-recognized text from each plate.
