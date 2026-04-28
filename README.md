# Adding-Sunglasses-to-Your-Passport-Photo-Using-OpenCV-Completion-requirements
## Name: khamalraaj S
# Regno: 212224230122
## Aim

To design a system that digitally places sunglasses onto a human face image using image processing techniques.

### Objective
To explore image overlay and compositing techniques
To implement masking and alpha blending
To understand Region of Interest (ROI) handling
To generate a simple augmented visual output

### Introduction

Image processing enables us to enhance and modify digital images for various applications. In this project, we simulate an augmented effect by placing sunglasses onto a face image.

A PNG image of sunglasses (with a transparent background) is aligned with the eye region of a face. The alpha channel of the PNG ensures smooth blending, making the sunglasses appear naturally integrated with the face.

### Methodology
1. Import the face image
2. Import the sunglasses image (PNG format with transparency)
3. Adjust the size of the sunglasses to fit the face
4. Separate the alpha channel for masking
5. Identify and extract the eye region (ROI)
6. Use masking to eliminate unwanted portions
7. Blend the sunglasses with the ROI
8. Insert the modified region back into the original image
### Algorithm
1. Begin
2. Read the input face image
3. Read the sunglasses image
4. Resize the sunglasses based on face dimensions
5. Split the image into color and alpha channels
6. Generate a mask using the alpha channel
7. Define the eye region (ROI)
8. Apply the mask to remove background from ROI
9. Apply the mask to isolate sunglasses
10. Merge both images using blending
11. Replace the ROI in the original image.
12. Display the final output
13. End
Output
### 1. Input Face Image

<img width="533" height="652" alt="image" src="https://github.com/user-attachments/assets/b37e5237-1da6-4277-b220-b76e5c295568" />

### 2. Masked eye region

<img width="523" height="222" alt="image" src="https://github.com/user-attachments/assets/09e8ee47-5ce0-4684-9b62-888d307666c7" />

### 3. Masked sunglass region

<img width="532" height="234" alt="image" src="https://github.com/user-attachments/assets/dd9f0d41-8e26-40cf-826e-149ae5d8a51b" />

### 4. Augmented Eye and Sunglass

<img width="500" height="263" alt="image" src="https://github.com/user-attachments/assets/195c91ee-d23f-4df9-9a8f-7ff7d3b415fa" />

### 5. Final Augmented Image

<img width="1241" height="737" alt="image" src="https://github.com/user-attachments/assets/bef9ef85-3a3c-4fff-91a3-59c219adcfb8" />

### Limitations
1. Eye region selection is done manually
2. Cannot handle multiple faces simultaneously
3. Alignment may differ depending on face orientation
4. Future Enhancements
5. Integration of automatic face and eye detection
6. Support for live webcam processing
7. Addition of multiple accessories like caps, masks, etc.
8. Improved scaling and rotation handling

### Result
The system successfully overlays sunglasses onto the face image using masking and blending techniques, resulting in a visually realistic augmented image.
