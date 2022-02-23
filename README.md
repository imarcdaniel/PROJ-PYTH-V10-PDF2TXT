# PROJ-PYTH-V10-PDF2TXT
A small python script to scrape used dictionary  words from a PDFfor Wordle Clone Project. 


# DESCRIPTION
Most PDF files look like they contain well structured text. But the reality is that a PDF file does not contain anything that resembles a paragraphs, sentences or even words. When it comes to text, a PDF file is only aware of the characters and their placement.



### Requirements
- Python
- PyPDF2 [ pip install PyPDF2 ]


### Steps
Provide the following information :

1. Provide the path for your pdf here

pdfpath = input("Enter the pdf name file - use backslash when typing in directory path: ")   

2. Provide the output text file
txtpath = input("Enter the name of the desired txt file - use backslash forpath: ")   

### PS: The output files created will be stored in temp folder in the same directory by default.

3. python pdf2text.py
