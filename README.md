# MATLAB Image Processing App  
This project demonstrates various image‑processing operations using MATLAB App Designer.  
All output images are stored inside the **images_bundle/** directory.

---

## 📌 1. Original Image  
This is the uploaded RGB image.

![Original Image](images_bundle/27886e53-eb69-4139-8f4b-fcfb79eb5c96.png)

---

## 🎨 2. Grayscale Conversion  
Converted using `rgb2gray()` to remove color and keep intensity values.

![Grayscale](images_bundle/fb5e8827-41a8-4f19-97c7-ccbb5b680326.png)

---

## ⚫⚪ 3. Binary Image  
Generated using MATLAB `imbinarize()`, converting the grayscale image to pure black/white.

![Binary](images_bundle/ad63ab4a-176a-4cef-afdb-064753b382b1.png)

---

## 📊 4. RGB Histogram  
Shows the distribution of pixel intensities for Red, Green, and Blue channels.

![RGB Histogram](images_bundle/5ee76c94-4129-4b29-85c8-c62e84e91170.png)

---

## 📊 5. Grayscale Histogram  
Displays the intensity distribution of the grayscale image.

![Grayscale Histogram](images_bundle/ac3b3f26-e02d-488a-9c2c-90c18ed6a406.png)

---

## 📊 6. Binary / Edge Histogram  
Shows pixel counts for values 0 (black) and 1 (white) in binary or edge-detected images.

![Binary Histogram](images_bundle/b7f1b163-579d-4900-9f54-99272af733b5.png)

---

## 🔁 7. Complement of RGB Image  
Produces the negative version of the RGB image.

![Complement RGB](images_bundle/59f20f3d-8777-4f06-a763-005cc15572f1.png)

---

## 🔁 8. Complement of Grayscale/Binary Image  
Inverts pixel intensities:  
- Black ↔ White  
- Low ↔ High intensity

![Complement Gray](images_bundle/48df19e8-fb77-4d6a-89af-adf873714109.png)

---

## ✨ 9. Edge Detection (RGB)  
Extracts edges directly from the RGB image.

![Edges RGB](images_bundle/c4764e26-23b4-4970-a76e-cc284b8ba8da.png)

---

## ✨ 10. Edge Detection (Grayscale/Binary)  
Edges extracted after grayscale or binary conversion, usually giving cleaner results.

![Edges Gray](images_bundle/71b1f847-393d-4d59-ae7f-5d007230bc5e.png)

---

## ✅ Summary  
This app supports:  
- Image upload  
- RGB → Grayscale  
- Conversion to binary  
- Histogram visualization  
- Complement image  
- Edge detection  

All outputs are displayed inside the app and saved in **images_bundle/**.

