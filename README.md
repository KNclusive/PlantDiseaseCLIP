# CropHealthCLIP — Fine-Tuning CLIP for Crop Disease Detection

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Overview

**CropHealthCLIP** is a research-oriented project to fine-tune OpenAI’s CLIP model on crop disease imagery, enabling effective plant disease classification through contrastive learning.

## Key Features

- **CLIP-based fine-tuning** focused on agricultural image–text data.
- Leverages both *visual* and *textual* cues to enhance disease detection accuracy.
- Structured for extensibility to new crop types or disease labels.

## Setup & Usage

```bash
git clone https://github.com/KNclusive/CropHealthCLIP.git
cd CropHealthCLIP
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
