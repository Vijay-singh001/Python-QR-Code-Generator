# 🐍 Python QR Code Generator

This repository contains a simple yet effective Python script for generating QR codes. It demonstrates two methods: a quick, default generation for a URL, and a more customized approach to create a colored QR code with specific settings (version, error correction, box size, and border).

## ✨ Features

* **Simple Generation:** Quickly create a basic black-and-white QR code.
* **Custom Generation:** Control parameters like:
    * `version`: The size and data capacity of the QR code.
    * `error_correction`: The capacity for error recovery (`ERROR_CORRECT_H` is high).
    * `box_size`: How many pixels each box of the QR code is.
    * `border`: The thickness of the quiet border.
    * `fill_color` and `back_color`: Custom colors for the QR code.

## 🚀 How to Run the Script

### 1. Prerequisites

You'll need Python installed, and the following libraries:

```bash
pip install qrcode Pillow
