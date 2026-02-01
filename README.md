# 2023-SE-28-DIP-Task-10
Task 10
Create a Python script for Google Colab that performs JPEG-style compression on a user-uploaded color image. The script should:

Allow the user to interactively upload a color image.

Compress each RGB channel separately using 8×8 block-based Discrete Cosine Transform (DCT), followed by quantization and inverse DCT.

Include a demonstration of Huffman coding on one of the color channels.

Calculate and display the Compression Ratio (CR), Mean Squared Error (MSE), Peak Signal-to-Noise Ratio (PSNR), and Rate-Distortion (RD) values.

Show the original image, the compressed image, and a magnified difference image to highlight compression artifacts.

Allow the user to adjust compression strength through a scale_factor variable.

Use Matplotlib for displaying images and ensure that even subtle compression differences are visible in the difference image.
