# 🛂 Passport Photo Crop & Compress Tool
Demo : https://imageresizer.leapcell.app/


A lightweight web application designed to help users prepare photos for online forms with strict upload requirements (e.g., passport applications, visa forms). 

It allows users to crop images to exact pixel dimensions, correct rotation, and **automatically compresses** the file to meet maximum file size (KB) limits.

## 🚀 Features

*   **Pixel-Perfect Cropping:** Define exact target dimensions (default: 150px x 200px).
*   **Smart Compression:** Automatically reduces JPEG quality until the file fits under the size limit (default: 100KB).
*   **Rotation Control:** Straighten scanned photos using a slider or precise degree input.
*   **Live Preview:** See the final dimensions and calculated file size before downloading.
*   **Privacy First:** All image processing happens in the browser. No images are stored on the server.

## 🛠️ Tech Stack

*   **Frontend:** HTML5, CSS3, Vanilla JavaScript
*   **Image Processing Library:** [Cropper.js](https://github.com/fengyuanchen/cropperjs)
*   **Server (for hosting):** Node.js + Express

## 📂 Project Structure

```text
├── index.html       # The main application (UI + Logic)
├── server.js        # Simple Express server to serve the HTML
├── package.json     # Node dependencies and scripts
└── README.md        # Documentation
