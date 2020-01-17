# Deployment Manual

- The project will run on any server currently, but using on a local machine would probably make the most sense for now
- The file structure should be left alone for the moment.
- Launching the Pdf_In_Browser_1.sln will start/stop the project
- For troubleshooting the user must inspect the web page and read the console
    - The most vulnerable parts are currently loading the pages
    - We have been experienceing an error, on new downloads, with the pdfium.dll. The easiest fix is to replace the file into the file path listed if the error occurs.
- If an error occurs with a large PDF file then try opening a smaller PDF file to ensure everything is functioning properly.
