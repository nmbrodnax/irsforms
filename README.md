## OCR of IRS 990 Filings
This project involves using Python 3 to extract text from the IRS filings of nonprofit organizations (Form 990).

### Install the tools

From the command line, install the [Tesseract](https://github.com/tesseract-ocr) open-source OCRlibrary on MacOS using the package manager [Homebrew](https://brew.sh)
```
brew install tesseract
```

Test the installation (adapted from [this tutorial](http://www.pyimagesearch.com/2017/07))
```
tesseract data/example_01.png stdout
tesseract data/example_02.png stdout
tesseract data/example_03.png stdout
```

From the command line, install the `pillow` and `pytesseract` libraries
```
pip3 install pillow
pip3 install pytesseract
```

