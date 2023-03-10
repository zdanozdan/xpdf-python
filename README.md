# xpdf-python
Python wrapper around the pdftotext functionality of xpdf.

# Usage

```python
from xpdf_python.pdf_loader import PdfLoader

loader = PdfLoader("foo.pdf")
pdf_text = loader.extract_strings()
pdf_images = loader.extract_images()
```
