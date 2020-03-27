# Development Manual 

## Setting Up Project

For setting up the project you have download the repository https://github.com/abbiggs/PDF_ASP.Net .ZIP folder, and extract it (or clone the project). Make sure all the files stay in the same folder. We recommend opening the project in Visual Studio.

Your solution explorer should look like this if everything imported correctly:
![Solution Explorer](https://github.com/Brysonleeward/PDF-In-Browser-Rendering/blob/master/Auxiliary%20Files/SolutionExplorer.png)

If your solution explorer looks different then make sure that you have these nuget packages installed:
![Nuget packages](https://github.com/Brysonleeward/PDF-In-Browser-Rendering/blob/master/Auxiliary%20Files/NugetPackages2.png)

If your solution explorer looks different, or you have this message, you can try restoring the packages by following these steps:
![Nuget packages](https://github.com/Brysonleeward/PDF-In-Browser-Rendering/blob/master/Auxiliary%20Files/RestorePackagesMessage.png)
![Nuget packages](https://github.com/Brysonleeward/PDF-In-Browser-Rendering/blob/master/Auxiliary%20Files/Restore%20Step2.png)
![Nuget packages](https://github.com/Brysonleeward/PDF-In-Browser-Rendering/blob/master/Auxiliary%20Files/ClickRestore.png)


For troubleshooting you can also try cleaning:
![Solution Explorer](https://github.com/Brysonleeward/PDF-In-Browser-Rendering/blob/master/Auxiliary%20Files/CleanSolution.png)

and rebuilding your solution:
![Solution Explorer](https://github.com/Brysonleeward/PDF-In-Browser-Rendering/blob/master/Auxiliary%20Files/RebuildSolution.png)

If you are still missing things, or getting errors. Then you need to contact the development team for assistance.

## Additional Information

Currently this project is functional and it is converting PDF's into bitmap images. It then saves and displays these images in the browser as PNG files. There is also a hidden text layer that will allow for future editing and annotations.
- The back end is currently converting pdf's into bitmaps,
  which will is then pushed to the front end for displaying. 
- The front end is contained inside a single button. When the button is clicked
  it opens the pdf viewer.
  
Development Environment
- Back End
  - To duplicate the devlopment environment you will need:
    - Microsoft Visual Studio
    - PdfiumSharp C#/.Net pdfium wrapper
    - PdfiumSharp.Gdiplus
    - PdfiumSharp.Windows
    - Basic knowledge of C#
- Front End
  - To duplicate the development environment you will need:
    - Microsoft Visual Studio
    - HTML/Javascript knowledge / AJAX skill

The files listed under Development Environment --> Back End are required to be able to work with pdfium.
- PdfiumSharp is a C#/.Net wrapper that allows for C# development. It provides functionality to open, load,
  render, and save pdf's.
- PdfiumSharp.Gdiplus is an extention of PdfiumSharp that allows for individual pdf pages to be written 
  to bitmaps.
- PdfiumSharp.Windows contains the native pdfium binaries for Windows.
