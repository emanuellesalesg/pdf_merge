
This code uses the `PyPDF2` library to merge PDF files. First, it creates a PdfMerger object. 
Then, it lists and sorts all the files in the `files` folder. 
For each file that ends with `.pdf`, it adds it to the merger object. 
After all PDFs are added, the code creates a new file called `pdf_merged.pdf`, which contains all the combined PDFs from the folder.
