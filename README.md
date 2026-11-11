# Garment-Production-Cost-Analyser
A beginner Python project that reads garment production costs from a text file, extracts the relevant values and calculates the average production cost.  This project applies Python fundamentals to a practical fashion industry scenario, exploring how programming can support garment costing and buying decisions.
Concepts and Python Features Used

1. User Input

input() – Allows the user to enter the name of the text file they want to analyse.

2. File Handling

open() – Opens an external text file.

File objects – Stores the opened file so Python can read its contents.

for loop – Iterates through the file one line at a time.

3. Exception Handling

try – Attempts to execute code that may produce an error.

except – Handles errors when the requested file cannot be opened.

quit() – Terminates the program if the file cannot be found.

4. Conditional Logic

if statements – Checks whether a line meets a specified condition.

.startswith() – Identifies lines beginning with "UNIT COST:".

5. String Manipulation

.find() – Locates the position of the colon in a string.

String slicing – Extracts the text following the colon.

.strip() – Removes unnecessary whitespace from the extracted text.

6. Type Conversion

float() – Converts extracted text into a numerical decimal value.

7. Iteration and Variables

for loops – Processes each line in the text file.

Counters – Tracks the number of garment costs processed.

Accumulators – Maintains a running total of the extracted costs.

8. Mathematical Operations

Addition (+) – Adds individual garment costs to the running total.

Division (/) – Calculates the average production cost.

9. Output

print() – Displays the number of garments processed and the average production cost.

\n – Creates a line break in the output.

Skills Demonstrated

Reading and processing external text files.

Extracting structured information from unstructured text.

Converting string data into numerical values.

Performing calculations using loops and accumulators.

Handling basic file errors.

Applying programming to a real-world fashion buying scenario.

Future Improvements

Identify the highest and lowest garment production costs.

Calculate total production expenditure.

Introduce more robust input validation and error handling.

Expand the program to process additional garment information.
