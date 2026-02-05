# PDF Editor with Annotations

A desktop PDF editor application built with PyQt5 that allows you to add text annotations, merge, and split PDF files.

#Project Status: Work in Progress
**Note:** This application is currently under development. While core features like PDF merging and basic annotation work, some functionality may be incomplete or experimental. Feel free to contribute improvements!



# Features

- 📄 **PDF Viewing**: Open and view PDF files with zoom support
- ✏️ **Text Annotations**: Add text annotations to any page
- 🗑️ **Annotation Management**: Select, delete, or clear annotations
- 💾 **Save/Load Annotations**: Save annotations to JSON and load them later
- 🔗 **Merge PDFs**: Combine multiple PDFs and images into one PDF
- ✂️ **Split PDF**: Extract specific pages or page ranges
- 📤 **Drag & Drop**: Add files by dragging from file explorer
- 📱 **Responsive UI**: Clean and intuitive interface

## Screenshot

![PDF Editor Screenshot](screenshot.png)

# Installation

# Option 1: Run from Source
1. Install Python 3.8 or higher
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

  3. python app.py

  4. # Install PyInstaller
pip install pyinstaller

# Build executable
pyinstaller --onefile --windowed --name PDF_Editor app.py


