March 2026 <br>
I have built a script that will automatically populate the fields in the Common Data Set (CDS) fillable PDF using the fields from the excel file. This will reduce the potential for human error vs when copying data over manually, and it will save time. <br> 
<br>
This process can be used with python installed on your computer, but I have also included a .exe file which will work on any windows computer with no need to install python. <br>

# How to use: <br>
1. Download the cds pdf template file <br>
2. Download the cds excel template file and fill out with data. The python script loads in the "Answer Sheet" tab from that excel file.  <br>
3. From this github, download the excel_to_pdf.ipynb to run on your computer locally if you already have python installed. Or if you prefer not to use python, download excel_to_pdf.exe from the "CDS Excel to PDF" releases link on the right. Click the link and download just the .exe file.
4. Create a .env file with filepaths to the empty pdf template and filled excel template. I've uploaded env_sample.txt to this github, which you can download, change filepaths to where your data is, and then rename as ".env" (instead of env_sample.txt). Don't rename the variables, and do not include " " around the filepath. The .env file needs to be in the same folder as excel_to_pdf.ipynb or excel_to_pdf.exe. It doesn't matter where you put the template pdf/excel files, mine happen to be in the downloads folder. 
5. Run the python file or .exe file. <br>
<br>

Notes: <br>
1. The script is designed to output CDS_2025-2026.pdf. This file will be deleted/overwritten if you run again to avoid errors. <br>
2. A1 Main institution website and admissions website is broken. One pdf tag maps to both fields. You'll need to input manually. <br>
3. There may be bugs or unexpected errors. Please review the output carefully. I am not responsible for your data!
4. Feel free to reach out if you have questions/issues ywe4kw@virginia.edu
