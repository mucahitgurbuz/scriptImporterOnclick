# scriptImporterOnclick

Scripts loader onClick prevents unnecessary page load time for the moduler website
```
loadScript([
  'https://cdnjs.cloudflare.com/ajax/libs/jspdf/1.3.2/jspdf.min.js',
  'https://cdnjs.cloudflare.com/ajax/libs/html2canvas/0.4.1/html2canvas.min.js'
], pdfGenerate2D);
```

*loadScript* function will import required libraries for the function _pdfGenerate2d_ then runs the function. This process will reduce the initial page load time for the feature that is not initiated on page load. 
