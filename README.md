# Automatic Detection of Craters & Boulders from OHRC Images

This project aims to develop an AI/ML model to automatically detect craters and boulders from Orbiter High Resolution Camera (OHRC) images using AI/ML techniques.

## Objectives

- Design a model capable of automatically detecting all craters/boulders in an OHRC image, irrespective of their shape, size, and illumination conditions.
- Quantify the selenographic position and diameter of the detected craters/boulders.

## Expected Outcomes

- Polygonal shape file or shape-size information of craters/boulders with their location on the given OHRC images.

## Dataset Required

- OHRC datasets publicly available in PDS4 format on Chandrayaan Map Browse

## Suggested Tools/Technologies

- Programming languages: Python, C, C++ or other suitable languages
- Image processing techniques for crater detection
- AI/ML Models for Crater/Boulder Detection

## Expected Solution / Steps

1. Selenoreference the downloaded OHRC images using the auxiliary information provided with the images with appropriate projection information.
2. Prepare the training and testing data. Train the model.
3. Prepare the evaluation metrics for accuracy.

## Evaluation Parameters

- Accuracy: Precision of the detected craters/boulders with respect to the actual craters present in the image.
- Relevance: Degree to which the detected craters/boulders and associated information match the actual craters.

