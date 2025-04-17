Creating payment receipts

Using reportlab to create PDF.
Installation: 
pip install reportlab //Run this command in terminal

Approach:
- Import the necessary module.
- Prepare the data as a list of lists, where the first inner list contains the headers.
- Create a simple document template, specifying the paper size (A4 in this case).
- Retrieve a sample style sheet from the built-in options and customize the styles as needed.
- Once the style object is ready, pass the data along with the style sheet to the PDF object and build it.
