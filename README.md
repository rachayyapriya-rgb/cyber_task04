File Organizer using Python

This project is a simple File Organizer built using Python.
It automatically organizes files into folders based on their file extensions.

 Description

The program:

Scans a selected directory

Identifies file types (like .jpg, .pdf, .txt, etc.)

Creates folders for each file type

Moves files into their respective folders

This helps keep your system clean and organized.

 Technologies Used

Python 3

OS module

shutil module

 How It Works

The program reads all files in a folder.

It checks the file extension.

If a folder for that extension does not exist, it creates one.

The file is moved into the corresponding folder.

Example:

image.jpg  →  JPG folder
document.pdf  →  PDF folder
notes.txt  →  TXT folder

How to Run

Open skill_task_4.ipynb

Provide the directory path

Run all cells

Files will be automatically organized

Or run as a Python script:

python file_organizer.py

 Features

Automatically creates folders

Supports multiple file types

Simple and easy to use

Saves time in manual sorting
