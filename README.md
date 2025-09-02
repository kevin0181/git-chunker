# Git Chunker

Git Chunker is a lightweight Python tool that automatically commits and pushes files to your Git repository in configurable size chunks (default: 300MB).  
It helps you handle large file uploads efficiently and prevents exceeding Git's push size limits.

## Features
- ✅ Automatically splits commits into 300MB (or custom) chunks  
- ✅ Supports large files and multiple commits  
- ✅ Simple to set up and use with minimal configuration  

## Usage
1. Clone this repository
2. Add your large files to the project folder
3. Run the script:
   ```bash
   python auto_commit.py
