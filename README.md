# Presentation-to-Anki

A Python tool to convert PowerPoint (PPTX) and PDF presentations into AI-enhanced Anki flashcards using the Claude API.

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

## Installing Dependencies
pip install -r requirements.txt

## Running the application 
python presentation_to_anki.py

## How to Use Your Own API Key
1. Sign up for an account at Anthropic's Claude API and obtain your API key.
2. Replace "INSERT_YOUR_API_KEY_HERE" in the code with your actual API key.
3. Run the application.
