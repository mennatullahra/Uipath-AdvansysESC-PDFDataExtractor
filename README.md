# Uipath-AdvansysESC-PDFDataExtractor
## Advansys ESC Data Extractor - UiPath RPA Project

## Project Overview

The **Advansys ESC Data Extractor** is a Robot Process Automation (RPA) project developed using UiPath Platform. The purpose of this project is to automate the process of receiving emails from senders within the domain @Advansys-esc.com, processing PDF attachments named "Challenge3," and extracting specific fields from these PDFs. The extracted data includes mandatory fields such as Name, Phone, and Email, and optionally, Age and Gender. The extracted data is then written into an Excel file with appropriate headers. Finally, the bot sends an email back to the sender, attaching the extracted data in CSV format with the name "Challenge3.csv."

## Requirements

1. **Email Processing:**
   - The bot shall monitor incoming emails within the domain @Advansys-esc.com.
   - Emails shall contain PDF attachments named "Challenge3."
   - If there are multiple emails with the same sender or no PDF attachment in the email, the robot throws a Business Exception (BE).

2. **PDF Validation:**
   - The bot shall only process PDFs that contain "(Advansys ESC)" at the top of the page.

3. **Data Extraction:**
   - The bot shall extract the following fields from the PDFs:
     - Name, Phone, Email, Age, Gender.

4. **Data Storage:**
   - The extracted data shall be written into an Excel file with appropriate headers.

5. **Email Response:**
   - The bot shall send an email to the sender with the extracted data attached as a CSV file.
   - The attachment shall be named "Challenge3.csv."


## Supervision
This project has been done under the supervision of **ADVANSYS-ESC**, providing guidance and support throughout the development process.
