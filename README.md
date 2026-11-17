# EXP-1 Image Handling and Pixel Transformations Using OpenCV

## AIM
To write a Python program using OpenCV that performs the following operations:

1. Read and display an image.
2. Adjust the brightness of an image.
3. Modify the contrast of an image.
4. Generate a third image using bitwise operations.
5. Split and merge the B, G, R and H, S, V colour channels.

## SOFTWARE REQUIRED
- Anaconda – Python 3.7
- Jupyter Notebook (for interactive development and execution)
- OpenCV (`cv2`)
- NumPy
- Matplotlib

## ALGORITHM

**Step 1:** Load an image from the local directory and display it.

**Step 2:** Create a matrix of ones with the data type `float64` to adjust the image brightness.

**Step 3:** Create brighter and darker images by adding and subtracting the matrix from the original image. Display all three images.

**Step 4:** Modify the image contrast by creating two higher-contrast images using scaling factors of 1.1 and 1.2 without overflow correction. Display the original, lower-contrast and higher-contrast images.

**Step 5:** Split the image (`Boy.jpg`) into B, G and R colour components and display the individual channels.

**Step 6:** Merge the R, G and B channels and display the merged image along with the original image.

**Step 7:** Convert the image from BGR to HSV colour space, split it into H, S and V components, and display the individual channels.

**Step 8:** Merge the H, S and V channels and display the merged image along with the original image.

## PROGRAM DEVELOPED BY
- **Name:** [Your Name Here]
- **Register Number:** [Your Register Number Here]

## EXERCISE – 01

### 1. Read the image (`Eagle_in_Flight.jpg`) using OpenCV `imread()` as a grayscale image.

```python
# YOUR CODE HERE
```

### 2. Print the image width, height and channel.

```python
# YOUR CODE HERE
```

### 3. Display the image using Matplotlib `imshow()`.

```python
# YOUR CODE HERE
```

### 4. Save the image as a PNG file using OpenCV `imwrite()`.

```python
# YOUR CODE HERE
```

### 5. Read the saved image as a colour image using `cv2.cvtColor()`.

```python
# YOUR CODE HERE
```

### 6. Display the colour image using Matplotlib `imshow()` and print the image width, height and channel.

```python
# YOUR CODE HERE
```

### 7. Crop the image to extract a specific object (Eagle alone) from the image.

```python
# YOUR CODE HERE
```

### 8. Resize the image up by a factor of 2x.

```python
# YOUR CODE HERE
```

### 9. Flip the cropped/resized image horizontally.

```python
# YOUR CODE HERE
```

### 10. Read the image (`Apollo-11-launch.jpg`).

```python
# YOUR CODE HERE
```

### 11. Add the following text to the dark area at the bottom of the image (centred on the image).

```python
text = 'Apollo 11 Saturn V Launch, July 16, 1969'
font_face = cv2.FONT_HERSHEY_PLAIN

# YOUR CODE HERE: Use putText()
```

### 12. Draw a magenta rectangle that encompasses the launch tower and the rocket.

```python
rect_color = (255, 0, 255)

# YOUR CODE HERE
```

### 13. Display the final annotated image.

```python
# YOUR CODE HERE
```

### 14. Read the image (`Boy.jpg`).

```python
# YOUR CODE HERE
```

### 15. Adjust the brightness of the image.

```python
# Create a matrix of ones (with data type float64)

# matrix_ones = ...

# YOUR CODE HERE
```

### 16. Create brighter and darker images.

```python
img_brighter = cv2.add(img, matrix)
img_darker = cv2.subtract(img, matrix)

# YOUR CODE HERE
```

### 17. Display the images (Original Image, Darker Image, Brighter Image).

```python
# YOUR CODE HERE
```

### 18. Modify the image contrast.

Create two higher-contrast images using scaling factors of 1.1 and 1.2 without overflow correction.

```python
matrix1 = ...
matrix2 = ...

# img_higher1 = ...
# img_higher2 = ...

# YOUR CODE HERE
```

### 19. Display the images (Original, Lower Contrast, Higher Contrast).

```python
# YOUR CODE HERE
```

### 20. Split the image (`Boy.jpg`) into B, G and R components and display the channels.

```python
# YOUR CODE HERE
```

### 21. Merge the R, G and B channels and display them along with the original image.

```python
# YOUR CODE HERE
```

### 22. Split the image into H, S and V components and display the channels.

```python
# YOUR CODE HERE
```

### 23. Merge the H, S and V channels and display them along with the original image.

```python
# YOUR CODE HERE
```

## OUTPUT

The following outputs are obtained after executing the Python program:

1. Read and display an image.
2. Adjust image brightness.
3. Modify image contrast.
4. Generate a third image using bitwise operations.
5. Display individual B, G, R colour channels.
6. Merge and display RGB channels.
7. Display individual H, S, V channels.
8. Merge and display HSV channels.

## RESULT

Thus, the images were successfully read and displayed, brightness and contrast adjustments were performed, colour channels were split and merged, and image processing operations were implemented using Python and OpenCV.
