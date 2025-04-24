# Image Captioning Project

## Overview

This project implements an image captioning model based on [Show, Attend and Tell github repos](https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Image-Captioning?tab=readme-ov-file)

Last updated: 08/04/2025

## Dependencies

Included in `requirements.txt`:

- torch
- torchvision
- opencv-python
- h5py

## Installation

python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt

## User Guide

python caption.py -i image_folder\flicker8k\108898978_7713be88fc.jpg -m BEST_checkpoint_flickr8k_5_cap_per_img_5_min_word_freq.pth.tar -wm image_folder\WORDMAP_flickr8k_5_cap_per_img_5_min_word_freq.json -b 5

## References
