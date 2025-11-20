# MATLAB Image Processing App  
This project demonstrates basic and advanced image-processing operations using MATLAB App Designer.  
All output images are stored inside the **images/** folder.

---

## 📌 1. Original Image  
This is the uploaded RGB image.  
It represents the starting point before applying any processing techniques.

![Original](images/27886e53-eb69-4139-8f4b-fcfb79eb5c96.png)

---

## 🎨 2. Grayscale Conversion  
The RGB image is converted to grayscale using MATLAB’s `rgb2gray()` function.  
This step reduces the image to intensity values only, making it suitable for binary processing and edge detection.

![Grayscale](images/fb5e8827-41a8-4f19-97c7-ccbb5b680326.png)

---

## ⚫⚪ 3. Binary Image  
The grayscale image is thresholded using `imbinarize()`.  
Pixels become either **0 (black)** or **1 (white)**.  
Used to highlight structural features.

![Binary](images/ad63ab4a-176a-4cef-afdb-064753b382b1.png)

---

## 📊 4. RGB Histogram  
Displays the distribution of pixel intensities for each color channel:  
- **Red**  
- **Green**  
- **Blue**  

Useful for analyzing brightness, color dominance, and contrast.

![RGB Histogram](images/5ee76c94-4129-4b29-85c8-c62e84e91170.png)

---

## 📊 5. Grayscale Histogram  
Shows how intensity values are distributed in the grayscale image.  
This helps visualize the dynamic range and contrast.

![Grayscale Histogram](images/ac3b3f26-e02d-488a-9c2c-90c18ed6a406.png)

---

## 📊 6. Binary / Edges Histogram  
Visualizes the number of black and white pixels in the binary or edge-detected images.  
A simple bar representation of pixel value counts (0 or 1).

![Binary Histogram](images/b7f1b163-579d-4900-9f54-99272af733b5.png)

---

## 🔁 7. Complement of RGB Image  
Produces a negative version of the RGB image using `imcomplement()`.  
Dark areas become bright and vice versa.

![Complement RGB](images/59f20f3d-8777-4f06-a763-005cc15572f1.png)

---

## 🔁 8. Complement of Grayscale/Binary Image  
The grayscale or binary image is inverted.  
- Black ↔ White  
- Low intensity ↔ High intensity

![Complement Gray](images/48df19e8-fb77-4d6a-89af-adf873714109.png)

---

## ✨ 9. Edge Detection (RGB)  
Detects edges directly from the RGB image using algorithms like **Canny / Sobel**.  
Highlights structural boundaries.

![Edges RGB](images/c4764e26-23b4-4970-a76e-cc284b8ba8da.png)

---

## ✨ 10. Edge Detection (Grayscale/Binary)  
Edges extracted after converting to grayscale or binary.  
This often produces cleaner results since edge detectors rely on intensity gradients.

![Edges Gray](images/71b1f847-393d-4d59-ae7f-5d007230bc5e.png)

---

## ✅ Summary  
This app allows performing:  
- Image upload  
- RGB → Grayscale conversion  
- Binary conversion  
- Histograms  
- Complement images  
- Edge detection  

All results are automatically displayed and saved.

---

