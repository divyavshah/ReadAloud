# ReadAloud - Dictation Tool

A Python desktop application that converts text from Word and PDF files into speech, allowing users to listen to entire documents or selected text segments with adjustable dictation speed.

## Features

- **File Support:** Upload and read text from `.docx` (Word) and `.pdf` files.
- **Selective Dictation:** Listen to the entire text or just a selected portion.
- **Adjustable Speed:** Choose dictation speed from slow to fast (1–10 scale).
- **Real-time Speech:** Smooth, non-blocking text-to-speech using threading.
- **User-Friendly Interface:** Built with Tkinter, including scrollable text area and clear instructions.

## Technologies Used

- **Python 3**
- **GUI:** Tkinter
- **Text-to-Speech:** pyttsx3
- **Document Handling:** `python-docx`, `PyPDF2`
- **Threading:** `threading` module for smooth speech playback
  
## Installation

1. Clone the repository:  
   git clone <repository_url>

2. Navigate to the project folder:
   cd dictation-tool
3. Install dependencies:
   pip install pyttsx3 python-docx PyPDF2
4. Run the application:
   python dictation_tool.py
   
## Usage

1. Launch the application.
2. Click **Upload File** to choose a Word or PDF document.
3. Select the text in the text area if you want to dictate a specific portion.
4. Adjust the **dictation speed** using the slider.
5. Click **Start Dictation** to begin, and **Stop Dictation** to halt speech anytime.

## Screenshots

![Upload File](screenshots/upload_file.png)
*Upload Word or PDF files for dictation.*

![Dictation](screenshots/dictation.png)
*Listen to the text with adjustable speed.*

## Contributing

Contributions are welcome! Please submit issues or pull requests for improvements.
