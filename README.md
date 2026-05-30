# 📄 Report Card Data Extractor

A Python-based desktop application that uses computer vision and cloud AI to digitize physical report cards. The tool captures live video via DroidCam, extracts specific academic data (Name, USN, Course Codes, and Marks) using Google Cloud Vision OCR, and automatically exports the structured data into an Excel spreadsheet.

## ✨ Features
* **Live Camera Feed:** Streams video directly from a mobile device using DroidCam and OpenCV.
* **Region-Specific OCR:** Extracts targeted data fields from physical documents using the Google Cloud Vision API.
* **User-Friendly GUI:** Built with Tkinter for easy image capturing, previewing, and extraction.
* **Automated Data Entry:** Parses extracted text and automatically populates formatted Microsoft Excel (`.xlsx`) files.
* **Cross-Platform File Handling:** Automatically opens destination folders and exported spreadsheets on Windows, macOS, or Linux.

## 🛠️ Technologies Used
* **Language:** Python
* **Computer Vision:** OpenCV (`cv2`)
* **AI / OCR:** Google Cloud Vision API
* **GUI:** Tkinter, Pillow (`PIL`)
* **Data Management:** Openpyxl

## 🚀 Setup and Installation

### 1. Prerequisites
* Python 3.8+ installed on your machine.
* The [DroidCam](https://www.dev47apps.com/) app installed on your smartphone (for the camera feed).
* A Google Cloud account with the **Cloud Vision API** enabled.

### 2. Install Dependencies
Clone this repository, open your terminal, and install the required Python libraries:
```bash
pip install opencv-python pillow openpyxl google-cloud-vision
