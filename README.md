# PDF Measuring Tool

A web-based tool for measuring distances on PDF documents with calibration support.

## Features

- **PDF Upload**: Upload PDFs via button click or drag-and-drop
- **Two-Point Measurement**: Click any 2 points to measure the distance
- **Multiple Units**: View measurements in points (pt), millimeters (mm), and centimeters (cm)
- **Calibration**: Set a known distance to get accurate real-world measurements
- **Visual Feedback**: Points and lines drawn on the PDF with distance labels
- **Zoom & Navigation**: Zoom in/out and navigate multi-page PDFs

## Usage

1. Open `index.html` in a web browser
2. Upload a PDF document
3. (Optional) Click "Calibrate" and select 2 points on a known distance
4. Enter the actual measurement and click "Apply Calibration"
5. Click any 2 points on the PDF to measure distances

## How Calibration Works

1. Click the "Calibrate" button (turns blue when active)
2. Click 2 points on the PDF that represent a known distance
3. Enter the actual distance value and select the unit (mm, cm, inches, or pt)
4. Click "Apply Calibration"
5. All subsequent measurements will use this calibration

## Tech Stack

- Pure HTML/CSS/JavaScript
- PDF.js for PDF rendering
- Canvas API for drawing measurements

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge).

## License

MIT License
