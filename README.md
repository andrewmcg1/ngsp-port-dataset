# ngsp-port-dataset
This repository contains all images and labels of a "refueling port". The labels consist of 40 keypoints. The images where taken over many different angles and colors of the port.
Some data augmentations were applied to the images and saved as a part of the dataset. These augmentations were done to take advantage of the symmetry of the refueling port and reduce the overall amount of labeling that needed to be manually completed.

## Repository Structure
This repository uses branched to seperate iterations of the dataset and the raw images and labels. The raw branches do not contain any augmented training data.

### Branches

- V5
    - 5th version of the dataset, including augmentations
- rawV5
    - Images and labels used for the 5th dataset.