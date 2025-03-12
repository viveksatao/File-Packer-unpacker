# File-Packer-unpacker
The File Packer-Unpacker is a Command-Line Utility (CUI) built in Java that allows users to:

Pack multiple text files from a directory into a single packed file.

Unpack the packed file to restore the original text files.

This tool helps in reducing storage clutter, organizing multiple files into one, and simplifying file transfer and storage. 

Software Requirements

Java Development Kit (JDK) 8 or above

Any Java IDE (Eclipse, IntelliJ IDEA, VS Code) or a simple text editor

Works on Windows, macOS, and Linux

Hardware Requirements

Minimum 1 GHz Processor (Multi-core recommended)

Minimum 2GB RAM (4GB recommended)

A few MBs of free disk space (depends on file sizes)

Features

📂 Packing Functionality: Reads .txt files from a directory and stores them in a single packed file.

📤 Unpacking Functionality: Extracts files from the packed file while maintaining their original structure.

🔐 Ensures Data Integrity: Uses a structured 100-byte header to store filenames and sizes, ensuring correct retrieval.

🛠️ Error Handling: Manages missing files, permission issues, and invalid inputs gracefully.

🖥 Simple CUI Interface: Easy to use with menu-based input
