![Land Use](https://github.com/umerkay/satellite-imaging-segmentation/assets/20483712/deb80987-0ff8-443b-b461-480dd6bfb8f2)

# Land Use Segmentation with UNet
This notebook uses data that is part of the [DeepGlobe Challenge](https://arxiv.org/abs/1805.06561). A UNet architecture is used to predict segmentation maps of satellite imagery. The masks classify between 7 different classes for land use: urban, agriculture, rangeland, forest, water, barren, and unknown.

The dataset used in this notebook includes only the training set from the original land use segmentation challenge, as the challenge is over and ground truth masks for validation and test sets are no longer available. Masks were included as RGB color maps, with different (often overlaying) colors representing the different classes. Hence, the data is pre-processed to convert to class labels for training and evaluation.

This implementation is inspired in-part by this [medium article](https://baratam-tarunkumar.medium.com/land-cover-classification-with-u-net-aa618ea64a1b).
