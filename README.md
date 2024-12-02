# tfjs_model_usage

This repository contains code demonstrations of how to use Tensorflow.js models for the following topics: 

  0. Text prediction models (toxicity, BERT, embeddings)
  1. Image prediction models (mobilenet, coco)


## 0. Text prediction models

The purpose of this webapp is to demonstrate how to use existing Tensorflow.js text prediction models.

- toxicity: it uses a text passage as input. It predicts whether text contains toxic/negative language.
- BERT: it uses a text passage and a question as input. It answers the question using the passage text.
- embeddings: it creates embeddings from text sentences.

[Current working version] https://codesolutions2.github.io/tfjs_model_usage/text_index.html


## 0. Image prediction models

The purpose of this webapp is to demonstrate how to use existing Tensorflow.js image prediction models.

- mobilenet: it uses an image as input. It predicts the main object in the image.
- coco: it uses an image as input. It predicts multiple objects in the image, and gives the bounding box locations.

[Current working version] https://codesolutions2.github.io/tfjs_model_usage/image_index.html

In progress: posenet
