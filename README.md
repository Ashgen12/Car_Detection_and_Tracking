## Car Detection and Counter Web-App

🚗 **Overview:**
- Real-time car counter detection using YOLO and SORT algorithms.
- Flask web application with WebSocket for dynamic updates.

⚙️ **Technical Details:**
- Language Used: Python.
- Frameworks: OpenCV, YOLO, SORT.
- Web Application: Flask for hosting the video feed with real-time updates.
- Tracking Algorithm: SORT for object tracking.
- Neural Network: YOLO for object detection.
- Image Processing: NumPy, cvzone.
- Data: Pre-trained on COCO dataset for vehicle detection.
  
🏁 **How to Run:**
1. **Setup Environment:**
   - Install required packages: `pip install -r requirements.txt`.
   - Ensure correct paths for video file, YOLO weights, and graphics.
   - Use python 10 version for better experience.

2. **Run the App:**
   - Execute `python app.py` in the terminal.

3. **Access the Web Interface:**
   - Open your browser and go to `http://127.0.0.1:5000/`.

4. **Start/Stop Video Feed:**
   - Click "Start Video" button to initiate the video feed.
   - Click again to stop.

5. **View Vehicle Count:**
   - Real-time vehicle count dynamically displayed on the web page.

📝 **Notes:**
- Adjust detection and tracking parameters in app.py for customization.
- SORT algorithm fine-tuned for accurate tracking.
- WebSocket enables dynamic updates without refreshing.

Happy car counting! 🚦👀
