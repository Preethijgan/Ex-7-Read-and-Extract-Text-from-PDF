# Extract text from a PDF and save it to a text file.
## Aim:
To design a UiPath workflow that reads and extracts text from a scanned PDF file using Optical Character Recognition (OCR) and saves the extracted text into a text file.

## Procedure:
* Open UiPath Studio and create a new Process.
* In the Main.xaml workflow, drag and drop the following activities in sequence:
### Step 1: Read PDF With OCR
- File Name: Select the PDF file (e.g., C:\Users\admin\Documents\sample.pdf).
- OCR Engine: Choose Tesseract OCR.
* Output: Store the result in a variable named ScannedPDFText.
### Step 2: Message Box
- Display the variable ScannedPDFText to verify that the text has been correctly extracted from the PDF.
### Step 3: Write Text File
- Specify the file path where the extracted text should be saved (e.g., C:\Users\admin\Documents\output.txt).
- In the “Text” field, provide the variable ScannedPDFText.
- Save and Run the workflow.
- UiPath reads the scanned PDF using OCR, displays the extracted text in a message box, and then writes it into the specified text file.

<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/f519f141-70fa-4d9b-b9af-88e8e5f2158e" />

## Output:

#### Extracted Pdf

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/6f87f79a-c13e-4018-aeda-e1679dcf9478" />

#### Extracted text in a file
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/6a3c785d-509e-4b77-b15f-16f808b97276" />

## Result:
The workflow successfully reads the scanned PDF document, extracts its text content using the Tesseract OCR engine, and saves the recognized text into a text file. The extracted text is also displayed in a message box for verification.


