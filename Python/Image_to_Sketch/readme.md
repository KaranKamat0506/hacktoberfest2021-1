
# Convert Image to a Sketch using Python

Converting an image to a pencil sketch using opencv library.




## Installation

Install OpenCV with pip

```bash
  pip install opencv-python
```
## Implementation

**Step 1:** Pick an image you'd like to turn into a pencil drawing.
We're going to use a dog illustration. You have complete freedom to make your selection.

**Step 2:** Read the image in RGB format before converting it to grayscale. The image has now been converted to a classic black and white photo.

**Step 3:** Invert the grayscale image also called the negative image, this will be our inverted grayscale image. Inversion is basically used to enhance details.

**Step 4:** Finally create the pencil sketch by mixing the grayscale image with the inverted blurry image. This is done by dividing the grayscale image by the inverted blurry image.

We now got our pencil_sketch. So, display it using OpenCV.

![Logo](https://editor.analyticsvidhya.com/uploads/29368python-opencv.png)

    
