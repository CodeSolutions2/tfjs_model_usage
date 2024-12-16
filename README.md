# tfjs_model_usage

This repository contains code demonstrations of how to use Tensorflow.js models for the following topics: 

  0. Text prediction models (toxicity, BERT, embeddings)
  1. Image prediction models (mobilenet, coco, posenet)


## 0. Text prediction models

The purpose of this webapp is to demonstrate how to use existing Tensorflow.js text prediction models.

- toxicity: uses a text passage as input and predicts whether text contains toxic/negative content.
- BERT: uses a text passage and a Question as input, and answers the question using the passage text.
- embeddings: it creates embeddings from text sentences.

[Current working version] https://codesolutions2.github.io/tfjs_model_usage/text_index.html


## 0. Image prediction models

The purpose of this webapp is to demonstrate how to use existing Tensorflow.js image prediction models.

- mobilenet: uses an image as input and predicts the main object in the image.
- coco: uses an image as input and predicts multiple objects in the image, by giving the bounding box locations of each object.
- posenet: uses an image as input and predicts the location of human joints, thus allowing one to understand the human pose.

[Current working version] https://codesolutions2.github.io/tfjs_model_usage/image_index.html
