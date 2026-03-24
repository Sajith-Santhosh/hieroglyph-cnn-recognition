# Egyptian Hieroglyph Recognition using CNN

## Project Overview

This project focuses on the automatic recognition of ancient Egyptian hieroglyphs using deep learning techniques. The objective is to train a Convolutional Neural Network (CNN) capable of classifying hieroglyph symbols from images.

Egyptian hieroglyphs are complex visual symbols that appear in historical inscriptions, monuments, and archaeological artifacts. Manually identifying and cataloging these symbols is a time-consuming process that requires specialized expertise. Computer vision techniques provide a way to assist researchers by automatically detecting and recognizing glyphs from images.

The goal of this project is to build a **baseline deep learning model** that can learn visual representations of hieroglyph symbols and classify them accurately.

---

## Research Background

This project directly uses the dataset introduced in the research paper:

**Franken, M., & van Gemert, J. C. (2013).**  
*Automatic Egyptian hieroglyph recognition by retrieving images as texts.*  
Proceedings of the 21st ACM International Conference on Multimedia (MM '13), Pages 765–768.  
https://doi.org/10.1145/2502081.2502199

In this work, the authors created a dataset by manually annotating and segmenting nearly **4,000 hieroglyph images** extracted from photographs of inscriptions. The images were taken from scenes documented in the book *The Pyramid of Unas* by Alexandre Piankoff.

Each hieroglyph in the dataset was labeled according to the **Gardiner Sign List**, which is the standard classification system used in Egyptology for cataloging hieroglyph symbols.

The original research explored methods for recognizing hieroglyphs using **visual descriptors and image retrieval techniques**, combined with language models derived from Egyptian texts.

---

## Project Goal

The goal of this repository is to:

- use the **Franken Hieroglyph Dataset** to study automatic hieroglyph recognition
- train a **Convolutional Neural Network (CNN)** to classify hieroglyph symbols
- establish a **CNN model trained from scratch**
- evaluate how effectively modern deep learning methods can recognize ancient glyph shapes

This project focuses on building a baseline system that can later be extended with more advanced techniques such as improved architectures, data augmentation, or transfer learning.

---

## Dataset

The project uses the **Egyptian Hieroglyph Dataset compiled by Morris Franken**, which contains approximately **4,210 segmented hieroglyph images** belonging to **171 classes** (excluding unknown labels).

Key characteristics of the dataset:

- Hieroglyphs extracted from photographs of pyramid wall inscriptions
- Images labeled using the **Gardiner Sign List**
- Each image contains a **single segmented hieroglyph**
- Preprocessed images resized to **50 × 75 pixels**

The hieroglyphs were extracted from inscriptions documented in:

*The Pyramid of Unas – Alexandre Piankoff*

---

## Motivation

Hieroglyph recognition lies at the intersection of **computer vision, archaeology, and digital humanities**. Developing automated methods for recognizing these symbols can support the analysis, preservation, and indexing of ancient texts.

This project investigates how well modern deep learning models can learn visual representations of hieroglyphic symbols from a relatively small historical dataset.
