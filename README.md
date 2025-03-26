# Presentation-to-Anki

A Python tool to convert PowerPoint (PPTX) and PDF presentations into AI-enhanced Anki flashcards using the Claude API.
## Screenshots
<img src="https://github.com/user-attachments/assets/9796a63a-d4b3-41ff-ae35-346a98c72146" alt="Sample Image" width="700" height="700">
<img src="https://github.com/user-attachments/assets/d7411b0a-6cb2-4815-a6fb-aa84104a1f51" alt="Sample Image" width="300" height="700">
![Progress Bar](https://github.com/user-attachments/assets/d7411b0a-6cb2-4815-a6fb-aa84104a1f51)
![image](https://github.com/user-attachments/assets/3cca17bb-7eaa-4e03-9231-17b2634f8d2e)
![image](https://github.com/user-attachments/assets/ff22e3b5-98cc-403b-8b39-02d47a839326)
![image](https://github.com/user-attachments/assets/d51b3ff9-c11f-44c7-a5b9-f3b8d2146a77)


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

## **Setup Instructions**

### **Claude API Key**
This project requires a Claude API key to function. Sign up for an API key at [Claude's official website](https://console.anthropic.com/).
### **Downloading Anki**
This project requires Anki to function. Download Anki at [Anki's official website](https://apps.ankiweb.net/).
## Installation
1. Clone the repository:
```bash
https://github.com/alexmc1169/presentation-to-anki
cd Presentation-to-Anki
```
2. Installing Dependencies
```bash
pip install python-pptx PyPDF2 PyMuPDF genanki anthropic python-dotenv tkinter
```
## Configuration
1. Create a .env file in the project root:
```bash
touch .env
```
2. Open the .env file in a text editor and add your Claude API key:
```bash
CLAUDE_API_KEY=your_api_key_here
```
Replace your_api_key_here with your actual Claude API key.

## Usage
1. Run the application:
```bash 
python presentation_to_anki.py
```
2. The GUI will open. Follow these steps:
Click Browse to select your PowerPoint (.pptx) or PDF (.pdf) file.
Enter a name for your Anki deck.
Click Convert to Anki to generate flashcards.
3. The generated Anki deck (.apkg file) will be saved to your Downloads folder.


