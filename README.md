## Video Text Extraction and Frame Filtering

This Python script extracts text from frames of a video and filters the extracted data to remove repetitive and unwanted frames.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [Output](#output)
- [Customization](#customization)

## Introduction

This script processes a video and performs the following tasks:

1. Extracts text from the frames of the video using Optical Character Recognition (OCR) with EasyOCR.
2. Filters the extracted data to avoid saving repetitive text for consecutive frames with the same content.
3. Filters the extracted data to remove specific frames based on predefined criteria (e.g., excluding frames with certain frame numbers).

## Features

- Extracts text from frames of a video.
- Filters out repetitive text for consecutive frames.
- Allows excluding specific frames based on criteria (e.g., frame numbers to exclude).
- Saves the filtered data to a text file.

## Requirements

Before running the script, make sure you have the following dependencies installed:

- Python 3.x
- OpenCV (cv2)
- EasyOCR
- FFmpeg (for video conversion if needed)

## Usage
1. Clone this repository to your local machine.

2. Install the required dependencies as mentioned in the "Requirements" section.

3. Prepare your input video file and specify its path in the code.

4. Customize the code as needed (e.g., frame filtering criteria).


## Output
The script generates the following output:

1. Extracted frame images (if enabled).
2. A text file named extracted_vehicle_number.txt containing the extracted and filtered data.


## Customization
You can customize the following aspects of the code:

1. Input video path.
2. Output folder for frame images.
3. Frame filtering criteria (e.g., exclusion of specific frames).
4. OCR configuration and settings.
