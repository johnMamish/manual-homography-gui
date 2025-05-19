# manual-homography-gui

This gui allows you to specify a homography between 2 images (or sets of images) by manually clicking on key-points and then preview the homography.

![Demo Screenshot](media/demo_screenshot_1.png?raw=true)

### Requirements

This gui requires `numpy` (`pip3 install numpy`), `pyqt5` (`pip3 install pyt5`), and `cv2` (`pip3 install opencv-python`).

I've had some issues having both `pyqt5` and `opencv-python` installed on the same computer. I would get the following error:

```
pyqt5 qt.qpa.plugin: Could not load the Qt platform plugin "xcb" even though it was found.
```

The easiest workaround I've found is to install `opencv-python-headless` instead of `opencv-python`.

### How to use?

To use this gui, you first have to choose 2 images with the
