# Python Programs Collection

A collection of diverse Python applications demonstrating different concepts and utilities.

## Projects Overview

### 1. **File Organizer in Python**
Automatically organizes files in a folder by categorizing them into different types.
- **Features:**
  - Sorts files into folders: Images, Documents, Audio, Videos, Archives, Scripts
  - Supports multiple file extensions (.jpg, .png, .gif, .pdf, .mp3, .mp4, etc.)
  - Creates folders automatically if they don't exist
- **Run:** `python "File Organizer in Python/main.py"`

### 2. **Password Manager**
A secure password storage and retrieval application using clipboard functionality.
- **Features:**
  - Save passwords for different websites
  - Retrieve passwords and copy them to clipboard
  - Simple text-based storage
- **Dependencies:** `pyperclip`
- **Run:** `python "Password Manager/main/main.py"`

### 3. **PDF Merger**
A GUI application to merge multiple PDF files into a single document.
- **Features:**
  - Select multiple PDF files through file dialog
  - Merge PDFs in order
  - Save merged PDF with custom filename
  - Tkinter-based GUI interface
- **Dependencies:** `pypdf`, `tkinter`
- **Run:** `python "PDF Merger/main.py"`

### 4. **Quiz App in Python**
An interactive quiz application with multiple-choice questions.
- **Features:**
  - Multiple-choice questions on various topics
  - Score tracking
  - Immediate feedback on answers
  - Pre-loaded question bank
- **Run:** `python "Quiz App in Python/main.py"`

### 5. **Snake, Water & Gun**
A classic hand game implementation (similar to Rock, Paper, Scissors).
- **Features:**
  - Player vs Computer gameplay
  - Win/Loss tracking
  - Simple command-line interface
- **Run:** `python "Snake, Water & Gun/main.py"`

### 6. **Typing Speed Tester**
Measures typing speed and accuracy with real-time feedback.
- **Features:**
  - Random sentences for testing
  - Measures typing speed in WPM (Words Per Minute)
  - Calculates accuracy percentage
  - Time tracking
- **Run:** `python "Typing Speed Tester/main.py"`

### 7. **Water Drinking Reminder with Notifications**
A background application that sends periodic water drinking reminders.
- **Features:**
  - Desktop notifications every hour
  - Customizable reminder messages
  - Runs in the background
- **Dependencies:** `plyer`
- **Run:** `python "Water Drinking Reminder with Notifications/main.py"`

## Installation

To run all projects, install the required dependencies:

```bash
pip install pyperclip pypdf plyer
```

Or install individual packages as needed:
- **pyperclip** - For clipboard operations (Password Manager)
- **pypdf** - For PDF manipulation (PDF Merger)
- **plyer** - For system notifications (Water Drinking Reminder)

## Usage

Navigate to the project directory and run:
```bash
python main.py
```

Each project is self-contained and can be run independently.

