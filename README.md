# Python Fingerprint Recognition

Fingerprint recognition with SKimage and OpenCV

Requirements:
- NumPy
- SKimage
- OpenCV2


Works by extracting minutiae points using harris corner detection.

Uses SIFT (ORB) go get formal descriptors around the keypoints with brute-force hamming distance and then analyzes the returned matches using thresholds.

Usage:

1. Place 2 fingerprint images that you want to compare inside the database folder
2. Pass the names of the images as arguments in the console

![image](https://user-images.githubusercontent.com/64000769/217174340-e5f2bf39-0d54-4b00-bb90-fdb7725d8b4c.png)

