# Face Swap Application
![GitHub Created At](https://img.shields.io/github/created-at/Stonky-Boi/410_CODERS)
![GitHub contributors](https://img.shields.io/github/contributors/Stonky-Boi/410_CODERS)
![GitHub License](https://img.shields.io/github/license/Stonky-Boi/410_CODERS)

## Team: 410 CODERS  
**Members:**  
- Arnav Kumar  
- Naman Shetty  
- Gopesh Srinivasan  

**Tagline:** *Hacking the Future*  

## Problem Statement  

We participated in **3H-ACKATHON**, an internal hackathon organized by **GDSC (Google Developer Student Club) IIT Indore**, and selected **Problem Statement 14: Face Swap**.  

### Task Description  
Develop an application that can:  
- Detect and select a face from an input image.  
- Seamlessly swap it with another face provided by the user.  
- Accurately align facial features (eyes, nose, mouth) and ensure a natural blend with the target image.  

### Key Challenges  
- Implementing face detection and alignment algorithms to precisely identify facial features.  
- Using image processing techniques to blend swapped faces smoothly.  
- Handling variations in lighting, angles, and skin tones for a realistic effect.  

## Research & References  
To understand and implement facial landmark detection and face swapping, we referred to the following articles:  
1. [Facial Landmark Detection](https://medium.com/@RiwajNeupane/facial-landmark-detection-a6b3e29eac5b)  
2. [Creating a Face Swapping Tool with OpenCV and Python](https://medium.com/@ccpvyn/creating-a-face-swapping-tool-with-opencv-and-python-4d64fc332de3)  

## Development Process  
We extensively debugged using multiple AI tools and refined our implementation through testing. The application was developed in **Python** using **OpenCV**, **Dlib**, and **Gradio** for the interface.  

### Dependencies  
To run the application, install the following dependencies:  
```bash
# Install cmake (required for dlib)
apt-get install -y cmake

# Install required Python packages
pip install dlib opencv-python gradio
pip uninstall -y numpy
pip install numpy==1.23.5
```

## Implementation  
The application uses **Dlib's facial landmark detector** and **OpenCV's image processing** techniques to perform face swapping. The key functions implemented include:  
- **Facial landmark detection** using `dlib.get_frontal_face_detector()`.  
- **Affine transformation and triangulation** to warp facial features.  
- **Seamless cloning** using OpenCV to blend the swapped face into the target image.  

## Running the Application  
The main implementation is available in our Jupyter Notebook on GitHub:  
[🔗 410_Coders_2025.ipynb](https://github.com/Stonky-Boi/410_CODERS/blob/main/410_Coders_2025.ipynb)  

You can also try the live demo here:  
[🌐 Face Swap App](https://d4bcc4aadcb4ae815d.gradio.live/)  

## Usage  
1. Upload a **source face** and a **target image**.  
2. Click **Run** to swap the faces.  
3. The output will display the target image with the swapped face.  

---  
🚀 **410 CODERS - Hacking the Future** 🚀  
