# Getting-Started-with-OCR

## Description

Identify images based on the annotated labels provided in the samples.

## Installation

```sh
pip install -r requirements.txt

```

## Architechture

<p align="center">
  <img src="https://github.com/dipanjannC/raft-interview/blob/main/data/misc/model_architecture.png" width="750" title="Model Architechture">

</p>

1. Image Processing

   * Orientation Correction
   * Image Binarization
   * Denoising
   * Deskewing
   * Normalization
   * Image Scaling
   * Removing Horizontal and Vertical Lines
   * Enchaining Contrast
   * Image Segmentation through boxes
2. Text Processing

   * Basic Text Cleaning (like removing repetitive special characters)
   * Spelling Correction through SYMSPELL
   * NER - For Names and Locations
   * Keyword Extraction
   * Profiling Text Data
3. Text Embeddings

   * Transformers based Embeddings
   * Sentence Transformers based Embeddings
   * FastText Embeddings
4. Model Selection & Training
5. Model Evaluation

## Future Work

Some of the research findings are shared in the Document shared.
