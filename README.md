# Question scanner
This is version 0.2.1 of an App that scans questions and search for its answer. It uses Tesseract for OCR and React for UI. All existing questions are stored in `questions.json` file. The app will look for a question that contains normalized ("clean" without symbols) text in DB. If the question exist in DB, the answer will be shown on screen. Otherwise an "error message" is shown and the user can try again.

## Instructions
A simple Next single page app.
- Open the app.
- Take a photo of the text.
- Search for the answer or repeat the photo step if text cannot be read. 