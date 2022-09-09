# Site_Specific_Weed_Management

## Introduction
The loss in crop yield has to be taken into consideration for improving the return on investment
for people depending on agriculture as well as for strengthen the economy of the country. The
yield losses are caused by three major factors weed invasion, pests and pathogens, from which
weeds are a major issue.  Plants in the early-growth phase are heavily competing for nutrients and water and often this phase is crucial for a plant to prevail against all other seedings (weeds). Weeds are the unwanted plants that grow along with the crops e.g
Chickweed, Scentless Mayweed etc. Weed control is the process of reducing or eliminating the
loss in crop yield caused due to weeds

## Objective
Given an image, we want to accurately classify the 6 crop seedlings of interest. Hence, differentiating/detecting any unwanted plant (weed).

### About the dataset
The dataset consists of 6 classes of plants of RGB images, namely: 
- Blackgrass, 
- Charlock,
- Cleavers,
- Fat Hen, and
- Maize, and 
- Wheat.
## Preprocessing Methods
- **Preprocessing**: The image data were loaded into memory in a sorted manner. While the mask
set was loaded and binarized using the OpenCV package in
python. The datasets were divided into two parts, 80% for training and 20% for validation,
respectively. All images were resized to the same size (128 × 128) and normalised.
- **Data Augmentation**: Due to the small dataset available for training, data augmentation was employed to synthetically generate more training
images and their corresponding masks with varying rotation, flipping, e.t.c.

## Models Architecture
Several CNN architecture was used [and trained from scratch] using the Tensorflow open-source framework, namely:
- Custom CNN
- RestNet50
- MobileNet_V2
- Xception
- DenseNet201







