# Batch Script: Replace Word in Filenames

This batch script allows users to replace a specific word in filenames within a specified directory.

## Usage

1. Run the script.
2. Enter the word you want to replace and the word you want to add when prompted.
3. Enter the directory path where the filenames are located.

Example:
Enter the word you want to replace: old
Enter the word you want to add: new
Enter the directory path: C:\Users\Username\Documents

## Instructions

- The script prompts the user to enter the word to replace and the word to add.
- It then prompts for the directory path where the filenames are located.
- For each file in the specified directory (including subdirectories), the script renames the file by replacing occurrences of the specified word with the new word.
- After processing all files, the script completes execution.

## Requirements

- Windows operating system
- Command Prompt (cmd.exe)

## Notes

- The script only modifies filenames and does not alter file contents.
- Use caution when specifying directory paths to avoid unintended modifications.
