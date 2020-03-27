# Deployment Manual

What needs to be installed before starting:

## Prerequisites:
- Install Visual Studio from https://visualstudio.microsoft.com/vs/
- In the future we plan to include directions for deployment on a server. For now, we simply run the app locally. At the moment deployment is for windows based systems.

## Building and Compiling
- The following list will contain files and method names holding variables that are specific to the environment since there is no configuration file that the application reads on installation. This includes API endpoints, authentication settings, caching strategies, etc that will need to be changed.
    
#### Test Before Deployment
   - Once the prerequisites are installed, the next recommended step is to run the tests. You can run the tests by running the PDFiumBackTest.
    
#### Build and Compile
- In visual studios, run the file labeled PDF_In_Browser1. This should build and compile the project.
- For troubleshooting the user must inspect the web page and read the console
    - The most vulnerable parts are currently loading the pages
    - We have been experienceing an error, on new downloads, with the pdfium.dll. The easiest fix is to replace the file into the file path listed if the error occurs.
- If an error occurs with a large PDF file then try opening a smaller PDF file to ensure everything is functioning properly.
    -Other troubleshooting recommendations would be, after selecting the Pdf_In_Browser_1.sln file, click the build tab and select clean solution. Then repeat and rebuild the soluion.

#### Uploading to the Server
- In the future, we plan to include directions for deployment on a server. For now, we simply run the app locally, through Visual Studios. We are also planning to add crossplatform compatibilty but at the moment deployment is for windows based systems.

## Final Result
- If everything has gone correctly, this is how the project should look. You can see that it is running on a local server.
![Step 6](https://github.com/Brysonleeward/PDF-In-Browser-Rendering/blob/master/Auxiliary%20Files/zoomingin.png)
  
