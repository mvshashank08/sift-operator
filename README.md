# Implementing the SIFT Operator
This project is a part of my work toward the course `CS 682` - **Computer Vision** at *George Mason University (GMU)*.

I implemented the *Scale-Invariant Feature Transform (SIFT)* in Python. This is not a finished work by no means. There is lot that could be done to improve the performance in effectiveness and in runtime. This is inspired from [SamL98's PySIFT](https://github.com/SamL98/PySIFT).

I compared my implementation with *OpenCV's implementation of the SIFT operator* and *[tfeat](https://github.com/vbalnt/tfeat)* (a deep learning model to extract feature descriptor). I have made minor modifications for *tfeat* to run on CPU.

## Libraries Used
* `numpy`
* `matplotlib`
* `cv2` (OpenCV for Python)
* `scipy`
* `skimage`

## Files
* `Project.ipynb` - The entire code is provided in the notebook file.
* `Report.pdf` - The final report submitted for evaluation of my work.
* `SIFT-Paper.pdf` - The original SIFT paper from David Lowe.
* `images/` - The directory that has test images to run the algorithm on.
* `tfeat_master/` -  [tfeat](https://github.com/vbalnt/tfeat) repo directly downloaded
