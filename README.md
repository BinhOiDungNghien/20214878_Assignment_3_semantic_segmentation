What are transformation techniques you used?
 - Resizing: Resizes the input image to the specified dimensions (self.resize).
 - Color Space Conversion: Converts the color space of the image from BGR to HSV (in read_mask) and from BGR to RGB.
 - Color Thresholding (Creating Masks): Creates masks (red_mask and green_mask) based on specified color ranges.
 - Bitwise Operations (Combining Masks): Combines the red and green masks using a bitwise OR operation to create a full mask.
 - Data Type Conversion and Dimension Expansion: Expands the dimensions of the mask (np.expand_dims) and converts its data type to unsigned 8-bit integer.
 - Image Loading and Color Space Conversion: Reads the image in BGR format using OpenCV and then converts it to RGB format.

