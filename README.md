# Detecting Ships in Satellite Images

## Phases
- ✅ Train a **convolutional neural network** (CNN) to classify an image as either containing a ship or not.
- ⏱ Extend the CNN for **localization** so that it produces a bounding box around a ship if it detects one in the image.
- ⏱ Expand localization to **object detection** by using the extended CNN to find and bound the ships contained in the bay scenes.

## Dataset
In this set of satellite images, there are 4,000 small images and 10 large images:
- `archive/shipsnet`: Each of the 4,000 small images is an 80x80 RGB image, either of a ship or of a background with no ship.
- `archive/scenes`: Each of the 10 large images is an overhead snapshot of a bay, where ships are either sailing or docked.
> *Details and a download link can be found on [Kaggle](https://www.kaggle.com/datasets/rhammell/ships-in-satellite-imagery).*