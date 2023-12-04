# MD2GD
MarkDown to (ODT) Google Docs / Google Drive Conversion Colab

### Notebook Description and Usage Instructions

Google Drive does a horrible job of handling Markdown content from ChatGPT. This notebook is designed to convert ChatGPT Markdown content into an OpenDocument Text (ODT) file and save it to your Google Drive so you can edit it without losing all your formatting. 

#### How to Use the Notebook ([Markdown_Converter.ipynb](https://github.com/clarkdever/MD2GD/blob/main/Markdown_Converter.ipynb)):
1. **Install Dependencies**:
   - Run the first code block titled "Install the Dependencies". This step installs Pandoc and pypandoc, which are essential for the Markdown to ODT conversion process.

2. **Enter File Details**:
   - In the form field block titled "Enter file details", input the desired file name in the `file_name_input` field. Remember not to include the file extension; just enter the name.
   - In the `markdown_input` field, type or paste the Markdown content that you want to convert.

3. **Convert and Save**:
   - Execute the third code block titled "Run this to process the input and save your Markdown to Google drive". 

4. **Access Your File**:
   - Navigate to the ChatGPT folder in your Google Drive to access the newly created ODT file.

#### Additional Notes:
- Make sure to mount your Google Drive when prompted to ensure the notebook can save the ODT file correctly.
- File names should contain only letters, numbers, spaces, underscores, or hyphens.
- If an error occurs, read the error message for guidance on resolving the issue.
