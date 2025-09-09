---
layout: project
type: project
image: img/FileOrganizer.png
title: "Python File Organizer"
date: 2024
published: true
labels:
  - Python
summary: "A python project I built to find files I didn't use for 30 days."
---
This project was a Python script designed to automatically organize files in the Downloads folder by detecting items that had not been accessed in the last 30 days. Files that weren't used for a month were moved into a separate directory labeled “Not_used_for_30_days” on the desktop. The program relied on the os, shutil, and time libraries to handle file system operations, calculate last access times, and safely transfer files. This project functioned as a lightweight personal utility for decluttering and managing storage.

I developed the entire script. My role involved identifying a problem I encountered through university: Download folders filling with unused files—and designing a programmatic solution. I wrote the logic to iterate over the directory contents, filter out hidden files, calculate access times, and move qualifying files into the designated folder. I also added error handling to account for unexpected issues and print statements to inform the user about which files were moved.

Through this project, I gained practical experience with Python’s file system libraries and learned how to apply them to automate everyday tasks. I became more comfortable working with file paths, directory traversal, and conditional checks involving timestamps. This project also reinforced the importance of writing programs that can gracefully handle errors and provide useful user feedback. Most importantly, I saw how a relatively short script could save time and reduce digital clutter, which encouraged me to think about automation as a powerful tool for efficiency.
