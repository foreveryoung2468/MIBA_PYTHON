session 5: File Formats and Libraries

Overview

This repository contains the exercises for Session 5, focusing on the following topics:
1. File formats (JSON, Pickle, and Parquet).
2. Regular Expression Library (`re`).
3. Time and Date Handling Libraries (`datetime`).

The tasks involve working with annotation files, extracting and analyzing date information, and saving data in various formats.

Project Contents

This repository includes a Jupyter Notebook and related data files for processing and analyzing annotation files. The key objective is to extract date-related information from filenames and perform various operations based on the extracted data.

Key Exercises

1. Count Annotations by Month and Year
- Count the number of annotation files per month and year.
- Identify the month with the highest number of annotation files.

2. Create a Month-Based Annotation Dictionary
- Build a dictionary where:
  - **Key**: The month.
  - **Value**: A list of annotation file names corresponding to that month.
- Save this dictionary in JSON format, reload it to verify correctness.
- Save the dictionary again using Pickle format.
- Extend the dictionary to include annotation details as a dictionary with keys: `name` and `date` (using `datetime` objects).

3. Sort and Print Annotations by Date
- Print all annotations from the second half of 2024, sorted from the oldest to the newest.

---

How to Run

Prerequisites
Ensure the following are installed:
- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - `re`
  - `glob`
  - `os`
  - `json`
  - `pickle`
  - `datetime`
  - `collections`

Steps to Run

1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/session-5-exercises.git
   ```
2. Navigate to the repository directory:
   ```sh
   cd session-5-exercises
   ```
3. Open the Jupyter Notebook:
   ```sh
   jupyter notebook session_5.ipynb
   ```
4. Follow the prompts in the notebook to complete the exercises.

---

Code Logic Overview

Here is a brief explanation of the core logic for the exercises:

1. **Annotation File Parsing**:
   - Use regular expressions to extract date and time information from filenames.
   - Convert the extracted date and time into `datetime` objects for further analysis.

2. **Counting Files**:
   - Use `collections.Counter` to count the number of annotation files per month and year.
   - Identify the month and year with the highest number of annotations.

3. **Saving and Loading Dictionaries**:
   - Save the dictionary in JSON format and reload it to verify correctness.
   - Save the dictionary in Pickle format for performance optimization.

4. **Sorting by Date**:
   - Filter annotations for specific time ranges (e.g., the second half of 2024).
   - Sort and print the annotations chronologically.

---

Sample Outputs

Here are some example outputs from the code:

1. Month with the most annotations:
   ```
   Year-Month with the most annotations: (2024, 7), Count: 15
   ```

2. Example dictionary of annotations by month (JSON format):
   ```json
   {
       "2024-07": ["file1.txt", "file2.txt"],
       "2024-08": ["file3.txt"]
   }
   ```

3. Annotations from the second half of 2024 sorted by date:
   ```
   2024-07-15 12:30:00 - file1.txt
   2024-08-01 09:00:00 - file2.txt
   ...

