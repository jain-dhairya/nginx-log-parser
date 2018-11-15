# nginx-log-parser
Python script parses an NGINX access log.

# Description
This python script parses an NGINX access log and counts the total occurrences of a chosen item within the logs and outputs a dictionary. You can run this code using python 2 and 3.

## Important files
Input file - input.log (it can be any log file.)
Main python file - main.py (it has the code which basically count the total occurrences)
Output file - output.txt (has the generated output)

## Summary
In the input.log, it processes the "requested file/page" segment, this can be changed to any other segment of the log.

The output is useful when serving media assets as you can serve assets from source and calculate view counts periodically from the NGINX logs using this parser.
