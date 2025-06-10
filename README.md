Simple Python keylogger using the pynput library to capture keystrokes and save them to a file.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Configuration](#configuration)
- [Contributing](#contributing)


1. **Installation**
# clone repo
git clone https://github.com/yourusername/python-pynput-keylogger.git
cd python-pynput-keylogger

# create virtual env (optional but recommended)
python3 -m venv venv
source venv/bin/activate

# install dependencies
pip install -r requirements.txt

Usage
python keylogger.py
# Captured keys will be appended to keyfile.txt in the same directory.

Features

Captures all printable keystrokes

Appends to a persistent log file (keyfile.txt)

Handles special keys gracefully (e.g., Backspace, Enter) 

