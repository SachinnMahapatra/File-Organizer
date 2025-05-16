# 🗂️ File Organizer - Python Script

A handy and lightweight Python script that automatically organizes files in a directory by sorting them into folders based on file type.

---

## 🔍 What It Does

This script scans the directory it's run in (for example, your messy `Downloads` folder), identifies file types based on their extensions, and moves them into relevant folders like:

- 📷 `Images/` → `.jpg`, `.jpeg`, `.png`, `.gif`, etc.
- 📄 `Docs/` → `.pdf`, `.docx`, `.txt`, etc.
- 🎵 `Media/` → `.mp3`, `.mp4`, `.mkv`, etc.
- 📦 `Others/` → All other uncategorized file types

If the folders don’t exist, they will be automatically created.

---

## 🛠️ How It Works

1. Run the script in a directory (e.g., your Downloads).
2. It will loop through all the files in that folder.
3. Each file is checked against known extensions.
4. Files are moved into matching folders (`Images`, `Docs`, `Media`, `Others`).
5. If a matching folder doesn't exist, the script creates it first.

---

## ▶️ How to Use

### 📥 Step 1: Clone the Repository
```bash
git clone https://github.com/SachinnMahapatra/File-Organizer.git
cd File-Organizer

### 📥 Step 1: Run The Script
python main.py

### Example
## Before Running 
Downloads/
├── photo1.jpg
├── resume.pdf
├── music.mp3
├── video.mp4
├── notes.txt

## After Running 
Downloads/
├── Images/
│   └── photo1.jpg
├── Docs/
│   ├── resume.pdf
│   └── notes.txt
├── Media/
│   ├── music.mp3
│   └── video.mp4
├── Others/


### Author 
## Made with ❤️ by Sachin Mahapatra
## Contact: sachinmahapatra858@gmail.com
## Portfolio - https://sachin-mahapatra.netlify.app/