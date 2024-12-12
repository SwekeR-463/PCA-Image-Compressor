# PCA Image Compressor

**A Python-based image compression tool leveraging Principal Component Analysis (PCA).**

## How it Works:

1. **Image Loading:** Loads the image into a NumPy array.
2. **Data Preprocessing:** Flattens the image into a 2D array, where each row represents a pixel.
3. **PCA Application:** Applies PCA to reduce the dimensionality of the data.
4. **Feature Selection:** Selects the principal components that capture a significant portion of the variance.
5. **Image Reconstruction:** Reconstructs the image using the selected principal components.
6. **Image Saving:** Saves the compressed image.
