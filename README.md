# File Organizer Script

## Overview

This Python script is designed to help you organize files within a directory by moving them to specific subdirectories based on their file extensions. The script categorizes files into different predefined categories (e.g., Documents, Audio, Videos, Images) and moves them accordingly.

## Usage

1. **Prerequisites**:
   - You must have Python 3 installed on your system.

2. **Clone the Repository**:
   Clone this repository to your local machine or download the `organize_files.py` script.

3. **Run the Script**:
   Open a terminal or command prompt and navigate to the directory where the `organize_files.py` script is located.

4. **Execute the Script**:
   Run the script with the following command:


Replace `<directory_path>` with the path of the directory you want to organize.

5. **View the Organized Files**:
The script will organize the files within the specified directory based on their extensions into subdirectories. If a subdirectory doesn't exist, it will be created.

6. **Customization**:
- You can customize the predefined categories and file extensions by modifying the `SUBDIRECTORIES` dictionary in the script.

## Example

Suppose you have a directory called `UnorganizedFiles` that contains various files. To organize these files, you can run the script as follows:

```shell
python organize_files.py UnorganizedFiles
