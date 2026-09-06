---
title: "Sample InSAR Processing Script"
excerpt: "A Python script for automated Sentinel-1 interferogram generation"
---

## 📌 Overview
This script automates the generation of interferograms from Sentinel-1 data using the SNAP toolbox and Python.

## 🛠️ Requirements
- Python 3.8+
- ESA SNAP 9.0
- `snappy` (SNAP Python interface)
- `numpy`, `matplotlib`

## 📥 Download
[Download Script](/files/sample_script.py)

## ▶️ Usage
```bash
python sample_script.py --master S1A_20210101 --slave S1A_20210201
