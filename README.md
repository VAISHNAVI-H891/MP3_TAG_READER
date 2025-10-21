# 🎵 MP3 Tag Reader in C

The **MP3 Tag Reader** is a command-line utility written in **C language** that extracts and displays metadata (ID3 tags) from MP3 audio files.  
It demonstrates key concepts like **file handling**, **structures**, **bitwise operations**, and **command-line arguments** in C.

🧩 Overview

An MP3 file contains metadata — such as title, artist, album, year, genre — stored in ID3v1 or ID3v2 tag formats.
This project reads those tags from MP3 files and displays them neatly to the user.

The tool provides both view and edit capabilities for MP3 tags, making it a handy example of binary file processing in C.

⚙️ Features

✅ Extract metadata from MP3 files (Title, Artist, Album, Year, Genre, Comment)

✅ Support for ID3v1 tag reading (last 128 bytes of MP3 file)

✅ Simple command-line interface

✅ Edit and update existing MP3 tags

✅ Validate file format and handle errors gracefully

✅ Demonstrates modular and clean C programming style

🧮 Menu Operations

📂 View Tag Information – Display metadata like title, artist, album, year, and genre.

🖋️ Edit Tag Information – Modify specific tags (title, artist, album, etc.).

💾 Save Changes – Write modified tag data back to the MP3 file.

❌ Exit – Close the program.

## 💻 Command-Line Usage

# Compile the program
gcc main.c view.c edit.c validate.c -o mp3_tag_reader

# View MP3 tag details
./mp3_tag_reader -v song.mp3

# Edit a specific tag
./mp3_tag_reader -e song.mp3 --title "New Title"

# Display help menu
./mp3_tag_reader --help

## 🎓 Learning Outcomes

Understand MP3 file structure and ID3 tags

Read and write binary files in C

Manage strings and memory safely

Build a command-line interface with options

Apply modular programming with multiple C files

Handle input validation and debugging

Use Git and GitHub for version control and project documentation
