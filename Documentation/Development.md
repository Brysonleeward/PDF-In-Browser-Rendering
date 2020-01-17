# Development Manual 

Currently this project is functional and it is converting PDF's into bitmap images. It then saves and displays these images in the browser as jpegs.
- The back end is currently converting pdf's into bitmaps,
  which will is then pushed to the front end for displaying. 
- The front end is contained inside a single button. When the button is clicked
  it opens the pdf viewer.
  
Development Environment
- Back End
  - To duplicate the devlopment environment you will need:
    - Visual Studio Code
    - PdfiumSharp C#/.Net pdfium wrapper
    - PdfiumSharp.Gdiplus
    - PdfiumSharp.Windows
    - Basic knowledge of C#
- Front End
  - To duplicate the development environment you will need:
    - Visual Studio Code
    - HTML/Javascript knowledge / skill
  
There is currently no specific folder structure we are following. The project isn't 
advanced enough yet to require specific organization.

The files listed under Development Environment --> Back End are required to be able to work with pdfium.
- PdfiumSharp is a C#/.Net wrapper that allows for C# development. It provides functionality to open, load,
  render, and save pdf's.
- PdfiumSharp.Gdiplus is an extention of PdfiumSharp that allows for individual pdf pages to be written 
  to bitmaps.
- PdfiumSharp.Windows contains the native pdfium binaries for Windows.
