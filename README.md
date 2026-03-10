March 2026 <br>
I have built a script that will automatically populate the fields in the Common Data Set (CDS) fillable PDF using the fields from the excel file. This will reduce the potential for human error vs when copying data over manually, and it will save time.

# How to use: <br>
1. Download the cds pdf template file <br>
2. Download the cds excel template file and fill out with data. The python script loads in the "Answer Sheet" tab from that excel file.  <br>
3. From this github, download the excel_to_pdf.ipynb to run on your computer locally if you already have python installed, or download excel_to_pdf.exe if you don't want to use python.
4. Create a .env file with filepaths to the empty pdf template and filled excel template: <br>
&nbsp;&nbsp;&nbsp;&nbsp;excel_file_path=C:\Users\user1\Downloads <br>
&nbsp;&nbsp;&nbsp;&nbsp;pdf_file_path=C:\Users\user1\Downloads\CDS-PDF-2025-2026_PDF_Template.pdf <br>
The .env file needs to be in the same folder as excel_to_pdf.ipynb or excel_to_pdf.exe. It doesn't matter where you put the template pdf/excel files, mine happen to be in the downloads folder. I've uploaded env_sample.txt to this github, which you can download, change filepaths, and then rename as ".env" (instead of env_sample.txt).
5. Run the python file or .exe file. <br>
<br>

Notes: <br>
1. The script is designed to output CDS_2025-2026.pdf. This file will be deleted/overwritten if you run again to avoid errors. <br>
2. A1 Main institution website and admissions website is broken. One pdf tag maps to both fields. You'll need to input manually. <br>
3. There may be bugs or unexpected errors. Please review the output carefully. I am not responsible for your data!
