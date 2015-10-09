# pyPdf417
PDF417 Barcode Generator (alpha, currently supports only text-mode)

# Basic usage

```
from pdf417 import PDF417
pdf = PDF417('This is the text sample which will be converted to barcode')
pdf.save_to_png('mybarcode.png')
```
