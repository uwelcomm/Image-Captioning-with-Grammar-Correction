# Image Captioning with Grammar Correction

## Overview
This is a university project related to Computer Vision and Natural Language Processing.

The project generates captions for input images using a Transformer-based pretrained image captioning model. After generating the caption, the output sentence is passed to a grammar correction component to improve the fluency and grammatical quality of the final caption.

## Pipeline
1. Input image
2. Caption generation using a Transformer-based pretrained model
3. Grammar correction using a T5-based model
4. Final improved caption

## Technologies
- Python
- Deep Learning
- Computer Vision
- Natural Language Processing
- Transformer models
- BLIP-based image captioning
- T5 / HappyTransformer for grammar correction

## Project Structure
```text
.
├── main.ipynb
├── our_predict.py
├── our_trainer.py
├── our_models.py
├── prepare_data.py
├── models/
├── examples/
└── requirements.txt
