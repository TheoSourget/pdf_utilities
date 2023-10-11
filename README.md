# pdf_utilities
Tools to extract figures, tables and section text inside pdf.

## Installation
Tested with Python 3.11.5 
1. clone the repo in your project: 
```console
git clone https://github.com/TheoSourget/pdf_utilities.git
cd pdf_utilities
```
2. install requirements: 
```console
pip install -r requirements.txt
```

## Usage
If you've clone the repo inside your own code you just need to import the function in your script.

Exemple:
```python
import pdf_utilities.pdf_utilities as pdf_util
figures = extract_images(pdf_path="./pdf/exemple.pdf",save_folder="./save_figures/")
```