# SMART_ATTENDANCE_SYSTEM
Revolutionizing attendance with Python-based facial recognition in Jupyter. Seamlessly integrated, it uses OpenCV and face_recognition to detect and manage attendance data on Google Drive. Dynamic recognition prompts engagement, setting new standards in efficiency and facial recognition tech.


The Smart Attendance System, implemented in Python, revolutionizes attendance tracking through facial recognition technology. Seamlessly integrated into a Jupyter notebook, it interacts with a webcam stream using JavaScript. OpenCV and face_recognition enable real-time face detection and recognition. Attendance data, including names, branches, sections, and timestamps, is efficiently managed and stored in CSV files on Google Drive.

## Features

- **Facial Recognition:** Utilizes OpenCV and face_recognition for accurate real-time face detection.
- **Webcam Integration:** Seamlessly interacts with a webcam stream within a Jupyter notebook.
- **Cloud Storage:** Attendance data, including names and timestamps, is stored in CSV files on Google Drive.
- **User Interaction:** Dynamically displays recognition results and prompts user interactions for unknown faces.
  
## Setup and Usage

1. Clone the repository.
2. Install the required dependencies using `requirements.txt`.
3. Run the Jupyter notebook.

## FLOW OF THE WORKING
Certainly! Here's a simplified flow of the code:

1. **Import Libraries:**
   - Import necessary libraries such as OpenCV, NumPy, PIL, face_recognition, etc.

2. **Function Definitions:**
   - Define functions for converting JavaScript objects to OpenCV images, converting bounding box images, and performing face recognition.

3. **Initialize Cascade Classifier:**
   - Initialize the Haar Cascade face detection model.

4. **Create Folders:**
   - Create folders for storing photos and attendance data if they do not exist.

5. **Load Known Faces:**
   - Define a list of known faces along with their corresponding images.
   - Load known faces and their encodings using the face_recognition library.

6. **Initialize Student Information:**
   - Define information for known students such as name, branch, and section.

7. **Initialize Webcam and Stream:**
   - Initialize the webcam and streaming components using JavaScript within a Jupyter notebook.

8. **Initialize Attendance Sheet:**
   - Create or append to the attendance sheet (CSV file) for the current date.

9. **Start Webcam Stream:**
   - Start the webcam stream for real-time video capture.

10. **Perform Attendance:**
    - Continuously capture frames from the webcam stream.
    - Detect faces using Haar Cascade and perform face recognition using the face_recognition library.
    - Record attendance for known faces, prompt for information for unknown faces, and handle user interactions.
    - Display recognition results dynamically on the video stream.

11. **Data Storage:**
    - Efficiently manage and store attendance data, including names, branches, sections, and timestamps, in CSV files on Google Drive.

12. **User Interaction Display:**
    - Dynamically display recognition results and prompts for user interactions on the video stream using JavaScript integration.

13. **Loop and Delay:**
    - Implement a continuous loop to capture frames.
    - Introduce delays between frames to control the processing speed.

14. **End of Execution:**
    - End the execution when needed.
## Working and interface
<img width="960" alt="Screenshot 2024-01-15 103809" src="https://github.com/Sabavat-Jayanth-Naik/SMART_ATTENDANCE_SYSTEM/assets/130920035/16e5a29a-156b-496f-a527-f3396be519f4">
<img width="405" alt="Screenshot 2024-01-15 091209" src="https://github.com/Sabavat-Jayanth-Naik/SMART_ATTENDANCE_SYSTEM/assets/130920035/a350a529-e8b1-4896-9dcb-9623b0711674">



## Collaboration

- Contributions are welcome! Feel free to open issues or submit pull requests.
- For inquiries or collaboration opportunities, contact [SABAVAT JAYANTH NAIK](mailto:your.email@gmail.com).


