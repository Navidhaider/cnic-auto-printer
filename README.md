# CNIC / ID Card Auto-Printer 🖨️

A lightweight, purely client-side web application designed to eliminate the hassle of printing multiple copies of an ID card or CNIC on a single A4 sheet. 

For printers that lack auto-duplex (automatic double-sided printing), aligning the front and back of an ID card multiple times is tedious. This tool allows you to upload the front and back images once, automatically populates them into a 4-row grid, and lets you fine-tune the visuals before printing.

## ✨ Features

* **Drag & Drop Interface:** Easily load the front and back images of the card.
* **Auto-Grid Generation:** Upload once, and the app automatically mirrors the images across 4 rows (Front on the left, Back on the right).
* **Advanced Image Controls:**
  * **Layout:** X/Y Positioning, Zoom/Scale, Standard 90° Rotation, and Fine-tune Degree Rotation.
  * **Color Correction:** Adjust Brightness, Contrast, and Saturation for perfect print quality.
* **Print-Ready A4 Layout:** Exact CSS dimensions tailored for standard CR80 ID/CNIC sizes (85.6mm x 54mm) on an A4 sheet.
* **Hide Outlines:** Toggle border visibility on/off right before printing.
* **100% Privacy Focused:** Everything runs completely in your local browser using JavaScript. No images are uploaded to any server.

## 🛠️ Tech Stack

* HTML5
* CSS3 / Tailwind CSS (via CDN)
* Vanilla JavaScript

## 🚀 How to Use

1. Open `index.html` in any modern web browser.
2. Drag and drop your CNIC Front image into the first upload zone, and the Back image into the second.
3. Use the control sliders under each image to fix rotation, scale the image to fit the box, and adjust the brightness/contrast for printing clarity.
4. Check the **Hide Blocks / Borders** option if you don't want the black cut-lines to print.
5. Click **Print Copies**!

## 👨‍💻 Author

**Muhammad Naveed Haider**
* Developed under LOGICFECTUM LTD

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
