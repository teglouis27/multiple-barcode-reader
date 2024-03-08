--This project made pseudobarcodes as training data, and then tries to find them.

The project is in the format:

multiple-barcode-reader/
├── html/
│   ├── barcode-generator-simple.html
│   └── barcode-generator-updated.html
├── scripts/
│   ├── playwright-screenshot.js
│   ├── grayednode.js
│   └── barcodeEdgeDetector.py

#Installing Dependencies
npm install playwright
npm install jimp
pip install opencv-python-headless


#Running
node playwright-screenshot.js
node grayednode.js
python barcodeEdgeDetector.py
