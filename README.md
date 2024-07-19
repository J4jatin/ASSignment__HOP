## ASS Subtitle Transformer
This Python script reads an .ass (Advanced SubStation Alpha) subtitle file, processes the dialogue events, and writes a transformed version of the file. Each event in the transformed file is surrounded by the previous and next dialogue events.

## Features
Read: Reads an .ass subtitle file.
Parse: Identifies and extracts dialogue events from the file.
Transform: Surrounds each event with its previous and next events.
Write: Outputs the transformed events into a new .ass file.
Prerequisites
Python 3.x
Usage
Clone the repository or download the script files.

Prepare your input subtitle file. Ensure your input file is in the same directory as the script or provide the correct path.

Run the script:

bash
Copy code
python transform_subtitles.py
Input and Output files:

Place your input .ass file in the directory and name it input_subtitles.ass or adjust the script accordingly.
The transformed subtitles will be saved as output_subtitles.ass.
Example
Place your .ass subtitle file as input_subtitles.ass in the script's directory, then run the script. The transformed file will be created in the same directory as output_subtitles.ass.

Script Details
read_ass_file(file_path): Reads the lines from the specified .ass file.
write_ass_file(file_path, lines): Writes the lines to the specified .ass file.
parse_events(lines): Extracts dialogue events from the lines.
transform_events(events): Surrounds each dialogue event with its previous and next events.
main(input_file, output_file): Main function to execute the script.
Contact
For any questions or feedback, please contact [Your Name] at [Your Email].

