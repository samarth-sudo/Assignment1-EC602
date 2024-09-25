**Title: Searcher**
# Assignment1-EC602


An executable (command line) script that explores the current directory and reports on matching files.

This report will go to the terminal (stdout).

Open a terminal and navigate to the directory where the script is located.

Run the script with the appropriate arguments. Examples:
**To search for Python files:**
python searcher.py "*.py"
**To search for files containing specific text:**
python searcher.py -c "search term"
**To search by file type (e.g., .xlsx):**
python searcher.py -t xlsx
**To filter files within a date range:**
python searcher.py --date 2021-01-01-2023-01-01
**To combine multiple conditions (AND logic):**
python searcher.py -c "def main" --date 2022-01-01-2023-01-01 "*.py"
