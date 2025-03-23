# Presentation-to-Anki

A Python tool to convert PowerPoint (PPTX) and PDF presentations into AI-enhanced Anki flashcards using the Claude API.
## Screenshots
![Main GUI](https://github.com/user-attachments/assets/9796a63a-d4b3-41ff-ae35-346a98c72146)
![Progress Bar](https://github.com/user-attachments/assets/d7411b0a-6cb2-4815-a6fb-aa84104a1f51)
![image](https://github.com/user-attachments/assets/3cca17bb-7eaa-4e03-9231-17b2634f8d2e)
![image](https://github.com/user-attachments/assets/799d4183-d378-4916-a903-57c7eb354398)

## Features
- **PPTX and PDF support**: Extracts text from both formats.
- **AI-powered flashcards**: Uses Claude API to generate high-quality questions and answers.
- **User-friendly GUI**: Built with Tkinter for easy navigation.
- **Progress tracking**: Displays real-time progress during file processing.
- **Automatic saving**: Saves the output deck to the user's Downloads folder.

## Technologies Used
- Python
- Tkinter (GUI)
- Claude API (AI)
- PPTX (PowerPoint parsing)
- PyPDF2 and PyMuPDF (PDF parsing)
- genanki (Anki deck creation)

## Installation
1. Clone the repository:
```bash
https://github.com/alexmc1169/presentation-to-anki
```
2. Installing Dependencies
```bash
pip install -r requirements.txt
```
3. Running the application
```bash 
python presentation_to_anki.py
```
## How to Use Your Own API Key
1. Sign up for an account at [Anthropic's Claude API](https://www.anthropic.com/) and obtain your API key.
2. Replace "INSERT_YOUR_API_KEY_HERE" in the code with your actual API key.
3. Run the application.
