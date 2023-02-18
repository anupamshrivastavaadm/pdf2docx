# pdf2docx
Convert Pdf to Docx

Here's an explanation of how to convert a PDF to a DOCX file using the PyPDF2 and docx libraries in Python:

1. Install PyPDF2 and docx libraries: 
   The first step is to install the required libraries. You can use pip to install both libraries.
   
2. Set the input and output file paths: 
   The next step is to define the input and output file paths. You will need to specify the full file path for both the input PDF and the output DOCX file.
   
3. Open the PDF file: 
   Use the open function to open the input PDF file. You should open the file in binary mode using the "rb" mode.
   
4. Read the PDF content: 
   Use the PyPDF2.PdfReader class to read the content of the PDF file. You can use the pdf_reader.pages[page] method to get 
   the number of pages in the PDF file, and the getPage method to get the content of each page.
   
5. Create a new Word document: Use the docx.Document class to create a new Word document.

6. Add the PDF content to the document: Use the add_paragraph method to add the PDF content to the Word document.
   You can also add images and tables using other methods provided by the docx library.
   
7. Save the document: Use the save method to save the Word document to the output file path.

That's it! Once you run this code, you should have a new DOCX file with the content of the input PDF file.
