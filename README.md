# Project Name

INT3404E 20 - Image Processing: Sino-Nom Character Retrieval

## Goals
This repository finds the five 3D models from a given database with the highest similarity to the 2D query image.

## Description

Task 3: Sino-Nom Character Retrieval with input is a 2D query image, and output is the five 3D models from a given database with the highest similarity.

Some implemented methods:Template matching, Scale-invariant feature transform (SIFT), Oriented FAST and Rotated BRIEF (ORB).

## Structure of repository
Sino-Nom Character Retrieval/ \
├── Report/ \
│   └── Final_Report.pdf \
├── simp-method.inpynb \
├── Sift-method.inpynb \
├── README.md

## Result
Here are our results obtained from experiments:

| Method            | Database   | Pairs      |
| ----------------- | ---------- | ---------- |
| Template matching | 0.8805     | 0.7671     |
| SIFT              | 0.7613     | 0.7225     |
| HOG               | 0.7533     | 0.7589     |

## Contributors
 + Hoàng Phi Hùng - 21020738