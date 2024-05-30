# Project Name

INT3404E 20 - Image Processing: Sino-Nom Character Retrieval

## Goals
This repository finds the five 3D models from a given database with the highest similarity to the 2D query image.

## Description

Task 3: Sino-Nom Character Retrieval with input is a 2D query image, and output is the five 3D models from a given database with the highest similarity.

Some implemented methods:Template matching, Histogram of oriented gradient (HOG), Histogram (Hist).

## Structure of repository
Sino-Nom Character Retrieval/ \
├── Report/ \
│   └── Final_Report.pdf \
├── Hist-Method.ipynb \
├── Hog-Method.ipynb \
├── README.md \
├── simp-method.ipynb \

## Result
Here are our results obtained from experiments:

| Method            | Database   | Pairs      |
| ----------------- | ---------- | ---------- |
| Template matching | 0.8005     | 0.7671     |
| Hist              | 0.7613     | 0.7225     |
| HOG               | 0.7533     | 0.7589     |

## Contributors
 + Hoàng Phi Hùng - 21020738
