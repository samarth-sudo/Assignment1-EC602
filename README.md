# Assignment1-EC602 Searcher


An executable (command line) script that explores the current directory and reports on matching files.

This report will go to the terminal (stdout).

Open a terminal and navigate to the directory where the script is located.

Run the script with the appropriate arguments. 

**Use chmod +x searcher to make it executable**

**Move it to /usr/local/bin/ or any directory in your PATH to run it like a built-in command **

Examples:

**To search for Python files:**

searcher "*.py"

**To search for files containing specific text:**

searcher -c "search term"

**To search by file type (e.g., .xlsx):**

searcher -t xlsx

**To filter files within a date range:**

searcher --date 2021-01-01-2023-01-01

**To combine multiple conditions (AND logic):**

searcher -c "def main" --date 2022-01-01-2023-01-01 "*.py"
