## ASS Subtitle Transformer
This Python script reads an .ass (Advanced SubStation Alpha) subtitle file, processes the dialogue events, and writes a transformed version of the file. Each event in the transformed file is surrounded by the previous and next dialogue events.

## Features
Read: Reads an .ass subtitle file.
Parse: Identifies and extracts dialogue events from the file.
Transform: Surrounds each event with its previous and next events.
Write: Outputs the transformed events into a new .ass file.

## Prerequisites
Python 3.x


## Script Details
read_ass_file(file_path): Reads the lines from the specified .ass file.
write_ass_file(file_path, lines): Writes the lines to the specified .ass file.
parse_events(lines): Extracts dialogue events from the lines.
transform_events(events): Surrounds each dialogue event with its previous and next events.
main(input_file, output_file): Main function to execute the script.

## Contact
For any questions or feedback, please contact Jattin at jattinshahgli@gmail.com

