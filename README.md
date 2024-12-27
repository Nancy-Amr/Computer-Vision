Topics to be assessed.
1. Robust image preprocessing techniques.
2. Adaptive image enhancement and noise attenuation techniques.
3. Extraction of barcode from image via morphological operations / Hough transform / contours.
4. Applying the required geometric transformations to extract the region of interest (barcode bars).
5. Decoding the barcode (sample images are all encoded using the code 11 symbology).
Detail of the task.
This project aims to incorporate the material discussed in the course in a practical application, encouraging
students to explore said material in practice and how to apply it in an actual problem they are facing, such
as that of the captured image of a barcode to automatically scan the bars on the label emulating the
behaviour of real-life barcode scanners. By preprocessing the captured barcode label image, an undistorted,
noiseless, binarized (grayscale), clear barcode be obtained and decoded as shown in the linked guide above.
The barcode decoding portion of the project may not be fully explored in the course material, however; it
aims to expand the knowledge of students, and how they can apply their obtained knowledge on basics of
classical computer vision to implement a real-life standard through simple logic; in this case that is to decode
the position of pixels (representing the bars of the barcode) and their varying widths to decode the data
represented in the barcode. You should not attempt to read the text representation of the data at the
bottom of the barcode with machine/deep learning and should not use any external libraries other than
those discussed in the course labs.
