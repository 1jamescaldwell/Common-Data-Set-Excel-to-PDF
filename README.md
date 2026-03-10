March 2026 <br>
I have built a script that will automatically populate the fields in the Common Data Set (CDS) fillable PDF using the fields from the excel file. This will reduce the potential for human error vs when copying data over manually, and it will save time.

# How to use: <br>
1. Download the cds pdf template file <br>
2. Download the cds excel template file and fill out with data. The python script loads in the "Answer Sheet" tab from that excel file.  <br>
3. Create a .env file with filepaths to the empty pdf template and filled excel template: <br>
&nbsp;&nbsp;&nbsp;&nbsp;excel_file_path=C:\Users\user1\Downloads <br>
&nbsp;&nbsp;&nbsp;&nbsp;pdf_file_path=C:\Users\user1\Downloads\CDS-PDF-2025-2026_PDF_Template.pdf <br>
The .env file needs to be in the same folder as the python file or .exe file. It doesn't matter where you put the pdf/excel files, mine happen to be in the downloads folder. 
