Building Material Scoring System
This Python script provides a system for calculating scores based on different types of building materials used in a construction project. The script utilizes the Tkinter library for creating a simple graphical user interface (GUI) to upload a file containing building material data. After uploading the file, the script calculates scores for glass, recycled, stone, and wood materials, and then writes the results to a text file.
Prerequisites
•
Python 3.x
•
Tkinter library (usually included in Python standard library)
Usage
1.
Upload File: Click the "Upload File" button to select a file containing building material data. The file should have a specific format where building materials are represented as codes (e.g., G10 for glass with a score of 10).
2.
View Results: Once the file is uploaded, the script calculates scores for each type of building material and the total score. The results are written to a text file named scoring-results.txt, which is saved in the datafiles directory.
3.
Result File: The scoring-results.txt file contains a breakdown of scores for each material type as well as the total score.
File Format
•
The input file should be a text file where each line represents a row in the building.
•
Building materials are represented by codes:
•
G: Glass
•
R: Recycled
•
S: Stone
•
W: Wood
•
The code is followed by a numerical value representing the score for that material.
•
Materials in each row are separated by the pipe character (|).
Example of valid input:
Copy code
G10|R5|S8|W3 R12|G6|S4|W9 S7|W5|G3|R10
Note
•
This script assumes that the input file follows the specified format. Any deviation from the format may result in incorrect results or errors.
