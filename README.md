# Simple-Resume-Builder
Web based editor to create Resume in a customizable template

#### Features
- Resume content can be edited just like a normal document editor (cut,copy,undo etc).
- Entire sections can be added, reordered, removed just by cut,copy,pasting method.
- Section visibility can be toggled while retaining the content.
- Options provided in the left panel to modify the template and formatting.
- Sub-points can be added with various bullet styles and adjustable indentation.
- Script provided to merge multiple pages and compress the PDF.


#### Instructions- How to use this repository

- for easy working with project you need to keep it simple to understand and implement
-  firstly create 4 folders named css, js, images and fonts and keep index and python files in main folder
-  
- keep all files of css in one folder (css)
- keep all fonts at one folder(fonts)
- keep all .js files in single folder(js)
- keep .png file inside a folder named images

#### Using the merge & compress script
- You must be able to run python file on your system for this.
- Save the individual pages in PDF format with name ```1.pdf``` , ```2.pdf```
- Download the ```compress_pdf.py``` file and open it in a text editor.
- Set the following variables :
	- ```dir_path``` : Directory path where you saved the PDFs for individual page
	- ```num_of_pages``` : Number of files to merge (i.e. pages in your Resume)
	- ```out_file``` : Name of output file
- Run this python file.
- Note: As this creates a new PDF file, you may have to see permission settings or run with sudo on terminal.
- 
**Note** : Click the "VIEW INSTRUCTIONS" button in the editor to read usage instructions.

**Note** : Use Google Chrome
