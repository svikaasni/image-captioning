# Image Captioning AI

This project combines Computer Vision and Natural Language Processing to generate captions for images.

## Technologies Used
- Python
- TensorFlow / Keras
- ResNet50 for image feature extraction
- LSTM for caption generation

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run `train.py` to train the model.
3. Use `predict.py` to generate captions for new images.

## Dataset
Use Flickr8k or MS COCO dataset. Place image files and captions in the `data/` folder.

## Folder Structure
```
image_captioning_project/
│
├── data/              # Dataset (images + captions)
├── models/            # Trained models
├── train.py           # Model training script
├── predict.py         # Caption generation script
├── utils.py           # Helper functions
└── README.md          # Project overview
```
