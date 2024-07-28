# **SnapDetect**

## **Introduction**

**SnapDetect** is a powerful and user-friendly application designed for real-time object detection and image processing. Utilizing the YOLO (You Only Look Once) algorithm, SnapDetect offers accurate and efficient object detection in both images and live video streams. The application also provides a variety of image filters to enhance and transform visuals, making it a versatile tool for developers, researchers, and hobbyists.

## **Features**

- **Real-Time Object Detection:** Detect and identify objects in images and live video using the YOLO algorithm.
- **Image and Video Processing:** Process both static images and live video feeds from your webcam.
- **Versatile Image Filters:** Apply a range of filters, including edge detection, sharpening, embossing, and more.
- **User-Friendly Interface:** Intuitive and easy-to-navigate interface for seamless operation.

## **Installation**

### **Prerequisites**

Ensure you have the following installed on your system:
- Python 3.x
- Tkinter
- OpenCV
- NumPy
- PIL (Pillow)

### **Setup**

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/snapdetect.git
   cd snapdetect
   ```

2. **Download YOLO Model Files:**
   - Download the YOLO weight file, config file, and class names file.
   - Place these files in the `models/` directory.

## **Usage**

1. **Run the Application:**
   ```sh
   python snapdetect.py
   ```

2. **Load YOLO Model:**
   - Click the "Load YOLO Model" button and select the YOLO weight, config, and class names files.

3. **Select Image or Video:**
   - Click the "Select Image" button to choose an image from your file system.
   - Click the "Select Video" button to choose a video file.
   - Click the "Live Video" button to toggle live video from your webcam.

4. **Apply Filters:**
   - Use the filter buttons to apply different filters to your image or video.

5. **Object Detection:**
   - Click the "Detect Objects" button to perform object detection on the selected image or video.

6. **View and Save Results:**
   - The processed image or video will be displayed in the application window. You can save the results by clicking the "Save" button.


