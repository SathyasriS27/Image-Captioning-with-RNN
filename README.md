# Image-Captioning-with-RNN 🌇

## Aim 🔍
The aim of this project is to understand the principles of text pre-processing and vocabulary building.

## Built using 🛠️
* Python 

## Dataset used is 📊
This project will use a subset of the COCO "Common Objects in Context" dataset for image caption generation. COCO contains 330K images, of 80 object categories, and at least five textual reference captions per image. Our subset consists of nearly 5070 of these images, each of which has five or more different descriptions of the salient entities and activities, and we will refer to it as COCO_5070.

The dataset can be accessed here - [dataset]
The feature map provided, can be accessed here - [feature_map]

## Required Packages 📦
* pytorch
* matplotlib
* numpy
* os

## How the work has been divided 🪜
1. Designing a RNN based decoder
2. Training model with precomputed features
3. Generating test predictions on the test data
4. Caption Evaluation using cosine similarity
